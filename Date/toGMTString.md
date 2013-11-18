#### toGMTString 方法

  根据格林威治时间( GMT )把 Date 对象转换为字符串。

##### 语法:

  ```javascript
  dateObject.toGMTString();
  ```

##### 返回值:

  dateObject 的字符串表示。此日期会在转换为字符串之前由本地时区转换为 GMT 时区。
  
##### 注:

  推荐使用 toUTCString() 取而代之！
  
###### 示例:

  ```javascript
  var DATE = new Date();  

  console.log( DATE.toGMTString() );
  ```

###### 结果:

  ```javascript
  >>>
  Mon, 18 Nov 2013 03:03:43 GMT
  ```
