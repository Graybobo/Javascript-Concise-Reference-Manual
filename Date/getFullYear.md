#### getFullYear() 方法

  返回一个表示年份的 4 位数字。

##### 语法:

  ```javascript
  dateObject.getFullYear();
  ```

##### 返回值:

  当 dateObject 用本地时间表示时返回的年份。返回值是一个四位数，表示包括世纪值在内的完整年份，而不是两位数的缩写形式。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getFullYear() );
  ```

###### 结果:

  ```javascript
  >>>
  2013
  ```
