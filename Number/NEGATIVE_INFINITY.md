#### NEGATIVE_INFINITY 属性

  - NEGATIVE_INFINITY 属性表示小于 Number.MIN_VALUE 的值。
  - 该值代表负无穷大。

##### 语法:

  ```javascript
  Number.NEGATIVE_INFINITY
  ```

##### 说明:

  - Number.NEGATIVE_INFINITY 是一个特殊值，它在算术运算或函数生成一个比 JavaScript 能表示的最小负数还小的数（也就是比 -Number.MAX_VALUE 还小的数）时返回。
  - JavaScript 显示 NEGATIVE_INFINITY 时使用的是 -Infinity。这个值的算术行为和无穷大非常相似。例如，任何数乘无穷大结果仍为无穷大，任何数被无穷大除的结果为 0。

##### 注:

  在 ECMAScript v1 和其后的版本中，还可以用 -Infinity 代替 Number.NEGATIVE_INFINITY。
