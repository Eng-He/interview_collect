## str与repr的区别

有一点是可以肯定的：如果 `__repr__` 被定义而 `__str__` 没有，那么对象会自动设置 `__str__ = __repr__`

这意味着，几乎所有的对象你需要实现 `__repr__` 以便使用者更好地理解这个对象。然而实现 `__str__` 只是为了一个更漂亮的输出

实现 `__repr__` 是为了明确

实现 `__str__` 是为了可读性

