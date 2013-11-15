#### toTimeString 方法

  把 Date 对象的时间部分转换为字符串。

##### 语法:

  ```javascript
  dateObject.toTimeString();
  ```

##### 返回值:

  dateObject 的时间部分的字符串表示，由实现决定，使用本地时间表示。
  
###### 示例:

  ```javascript
  var DATE = new Date();  

  console.log( DATE.toTimeString() );
  ```

###### 结果:

  ```javascript
  >>>
  16:09:41 GMT+0800
  ```
