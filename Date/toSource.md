#### toSource 方法

  返回表示对象源代码的字符串。

##### 语法:

  ```javascript
  dateObject.toSource();
  ```

##### 注:

  该方法在 Internet Explorer 中无效。
  
###### 示例:

  ```javascript
  var DATE = new Date();  

  console.log( DATE.toSource() );
  ```

###### 结果:

  ```javascript
  >>>
  (new Date(1384323879074))
  string
  ```
