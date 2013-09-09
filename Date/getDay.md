#### getDay() 方法

  返回表示星期的某一天的数字。

##### 语法:

  ```javascript
  dateObject.getDay();
  ```

##### 返回值:

  dateObject 所指的星期中的某一天，使用本地时间。返回值是 0（周日） 到 6（周六） 之间的一个整数。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getDay() );
  ```

###### 结果:

  ```javascript
  >>>
  1
  ```
