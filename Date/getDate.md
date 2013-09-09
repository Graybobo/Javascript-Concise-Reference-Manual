#### getDate() 方法

  返回月份的某一天。

##### 语法:

  ```javascript
  dateObject.getDate();
  ```

##### 返回值:

  dateObject 所指的月份中的某一天，使用本地时间。返回值是 1 ~ 31 之间的一个整数。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getDate() );
  ```

###### 结果:

  ```javascript
  >>>
  9
  ```
