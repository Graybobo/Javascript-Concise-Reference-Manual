#### toPrecision 方法

  toPrecision() 方法可在对象的值超出指定位数时将其转换为指数计数法。

##### 语法:

  ```javascript
  NumberObject.toPrecision( num );
  ```
##### 参数说明:

  num - 必需。规定必须被转换为指数计数法的最小位数。该参数是 1 ~ 21 之间（且包括 1 和 21）的值。有效实现允许有选择地支持更大或更小的 num。如果省略了该参数，则调用方法 toString()，而不是把数字转换成十进制的值。

##### 返回值:

  返回 NumberObject 的字符串表示，包含 num 个有效数字。如果 num 足够大，能够包括 NumberObject 整数部分的所有数字，那么返回的字符串将采用定点计数法。否则，采用指数计数法，即小数点前有一位数字，小数点后有 num-1 位数字。必要时，该数字会被舍入或用 0 补足。

##### 异常抛出:

  - 当调用该方法的对象不是 Number 时抛出 TypeError 异常。
  - 当 num 太小或太大时抛出异常 RangeError。1 ~ 21 之间的值不会引发该异常。有些实现支持更大范围或更小范围内的值。

###### 示例:

  ```javascript
  var Num = new Number( 9000 ),
      n = Num.toPrecision( 3 );
	  
  console.log( n );
  ```

###### 结果:

  ```javascript
  >>>
  9.00e+3
  ```
