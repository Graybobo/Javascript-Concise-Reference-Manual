#### toSource 方法

  返回表示对象源代码的字符串。

##### 语法:

  ```javascript
  arrayObject.toSource();
  ```

##### 注:

  该方法在 Internet Explorer 中无效。
  
###### 示例:

  ```javascript
  var Arr = [11, 2, 73, 41, 53, 6, 38, 9, 40],
      s = Arr.toSource();
	  
  console.log( s );
  console.log( typeof s );
  ```

###### 结果:

  ```javascript
  >>>
  [11, 2, 73, 41, 53, 6, 38, 9, 40]
  string
  ```
