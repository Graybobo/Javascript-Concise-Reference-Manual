#### getMonth() 方法

  返回表示月份的数字。

##### 语法:

  ```javascript
  dateObject.getMonth();
  ```

##### 返回值:

  dateObject 的月份字段，使用本地时间。返回值是 0（一月） 到 11（十二月） 之间的一个整数。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getMonth() );
  ```

###### 结果:

  ```javascript
  >>>
  8
  ```
