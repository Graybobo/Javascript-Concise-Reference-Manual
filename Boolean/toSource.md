#### toSource 方法

  返回表示对象源代码的字符串。

##### 语法:

  ```javascript
  booleanObject.toSource();
  ```

##### 注:

  该方法在 Internet Explorer 中无效。
  
###### 示例:

  ```javascript
  var Bool = new Boolean( false ),
      s = Bool.toSource();
	  
  console.log( s );
  console.log( typeof s );
  ```

###### 结果:

  ```javascript
  >>>
  (new Boolean(false))
  string
  ```
