#### valueOf 方法

  - valueOf() 方法可返回 String 对象的原始值。
  - 原始值是由从 String 对象下来的所有对象继承的。
  - valueOf() 方法通常由 JavaScript 在后台自动进行调用，而不是显式地处于代码中。

##### 语法:

  ```javascript
  stringObject.valueOf();
  ```

##### 返回值:

  stringObject 的原始值。

##### 异常抛出:

  当调用该方法的对象不是 String 时抛出 TypeError 异常。
  
###### 示例:

  ```javascript
  var Str = "Hello KILLHAPPY",
      s = Str.valueOf();
	  
  console.log( s );
  console.log( typeof s );
  ```

###### 结果:

  ```javascript
  >>>
  Hello KILLHAPPY
  string
  ```
