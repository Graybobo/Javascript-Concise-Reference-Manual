#### POSITIVE_INFINITY 属性

  - POSITIVE_INFINITY 属性表示大于 Number.MAX_VALUE 的值。
  - 该值代表正无穷大。

##### 语法:

  ```javascript
  Number.POSITIVE_INFINITY
  ```

##### 说明:

  - Number.POSITIVE_INFINITY 是一个特殊值，它在算术运算或函数生成一个比 JavaScript 能表示的最大的数还大的数（也就是比 Number.MAX_VALUE 还大的数）时返回。
  - JavaScript 显示 POSITIVE_INFINITY 时使用的是 Infinity。这个值的算术行为和无穷大非常相似。例如，任何数乘无穷大结果仍为无穷大，任何数被无穷大除的结果为 0。

##### 注:

  在 ECMAScript v1 和其后的版本中，还可以用 Infinity 代替 Number.POSITIVE_INFINITY。
