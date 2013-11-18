#### toUTCString 方法

  根据世界时( UTC )把 Date 对象转换为字符串。

##### 语法:

  ```javascript
  dateObject.toUTCString();
  ```

##### 返回值:

  dateObject 的字符串表示，用世界时表示。
  
###### 示例:

  ```javascript
  var DATE = new Date();  

  console.log( DATE.toUTCString() );
  ```

###### 结果:

  ```javascript
  >>>
  Mon, 18 Nov 2013 03:59:27 GMT
  ```
