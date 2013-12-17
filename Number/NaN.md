#### NaN 属性

  NaN 属性是代表非数字值的特殊值。该属性用于指示某个值不是数字。可以把 Number 对象设置为该值，来指示其不是数字值。

##### 语法:

  ```javascript
  Number.NaN
  ```

##### 说明:

  - Number.NaN 是一个特殊值，说明某些算术运算（如求负数的平方根）的结果不是数字。方法 parseInt() 和 parseFloat() 在不能解析指定的字符串时就返回这个值。对于一些常规情况下返回有效数字的函数，也可以采用这种方法，用 Number.NaN 说明它的错误情况。
  - JavaScript 以 NaN 的形式输出 Number.NaN。请注意，NaN 与其他数值进行比较的结果总是不相等的，包括它自身在内。因此，不能与 Number.NaN 比较来检测一个值是不是数字，而只能调用 isNaN() 来比较。
  - 在 ECMAScript v1 和其后的版本中，还可以用预定义的全局属性 NaN 代替 Number.NaN。
  - ( 请使用 isNaN() 来判断一个值是否是数字。原因是 NaN 与所有值都不相等，包括它自己。 )
