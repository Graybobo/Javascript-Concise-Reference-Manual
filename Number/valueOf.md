#### valueOf 方法

  - valueOf() 方法可以字符串返回数字。
  - 字符串的输出通常等于该数字。
  - valueOf() 方法通常由 JavaScript 在后台自动进行调用，而不是显式地处于代码中。

##### 语法:

  ```javascript
  NumberObject.valueOf();
  ```

##### 返回值:

  NumberObject 的原始数值。

##### 异常抛出:

  当调用该方法的对象不是 Number 时抛出 TypeError 异常。
  
###### 示例:

  ```javascript
  var Num = new Number( 1000 ),
      n = Num.valueOf();
	  
  console.log( n );
  console.log( typeof n );
  ```

###### 结果:

  ```javascript
  >>>
  1000
  number
  ```
