#### toDateString 方法

  把 Date 对象的日期部分转换为字符串。

##### 语法:

  ```javascript
  dateObject.toDateString();
  ```

##### 返回值:

  dateObject 的日期部分的字符串表示，由实现决定，使用本地时间表示。
  
###### 示例:

  ```javascript
  var DATE = new Date();  

  console.log( DATE.toDateString() );
  ```

###### 结果:

  ```javascript
  >>>
  Fri Nov 15 2013
  ```
