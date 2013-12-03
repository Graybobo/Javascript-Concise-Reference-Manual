#### toSource 方法

  返回 Math 对象源代码的字符串。

##### 语法:

  ```javascript
  Math.toSource();
  ```

##### 注:

  该方法在 Internet Explorer 中无效。
  
###### 示例:

  ```javascript
  var s = Math.toSource();
  
  console.log( s );
  console.log( typeof s );
  ```

###### 结果:

  ```javascript
  >>>
  Math
  string
  ```
