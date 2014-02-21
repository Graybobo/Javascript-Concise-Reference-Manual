#### anchor 方法

  anchor() 方法用于创建 HTML 锚。

##### 语法:

  ```javascript
  stringObject.anchor( anchor_name );
  ```
##### 参数说明:

  anchor_name - 必需。为锚定义名称。

###### 示例:

  ```javascript
  var Str = "KILLHAPPY",
      n = Str.anchor("anchor");
	  
  console.log( n );
  ```

###### 结果:

  ```javascript
  >>>
  <a name="anchor">KILLHAPPY</a>
  ```
