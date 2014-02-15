#### toExponential 方法

  把对象的值转换成指数计数法。

##### 语法:

  ```javascript
  NumberObject.toExponential( num );
  ```
##### 参数说明:

  num - 必需。规定指数计数法中的小数位数，是 0 ~ 20 之间的值，包括 0 和 20，有些实现可以支持更大的数值范围。如果省略了该参数，将使用尽可能多的数字。

##### 返回值:

  返回 NumberObject 的字符串表示，采用指数计数法，即小数点之前有一位数字，小数点之后有 num 位数字。该数字的小数部分将被舍入，必要时用 0 补足，以便它达到指定的长度。

##### 异常抛出:

  - 当调用该方法的对象不是 Number 时抛出 TypeError 异常。
  - 当 num 太小或太大时抛出异常 RangeError。0 ~ 20 之间的值不会引发该异常。有些实现支持更大范围或更小范围内的值。

###### 示例:

  ```javascript
  var Num = new Number( 3000 ),
      n = Num.toExponential( 1 );
	  
  console.log( n );
  ```

###### 结果:

  ```javascript
  >>>
  3.0e+3
  ```
