#### setUTCDate() 方法

  根据世界时( UTC )设置一个月中的某一天

##### 语法:

  ```javascript
  dateObject.setUTCDate( day )
  ```

##### 参数说明:

  day -- 必需。要给 dateObject 设置的一个月中的某一天，用世界时表示。该参数是 1 ~ 31 之间的整数。

##### 返回值:

  调整过的日期的毫秒表示。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();  
  DATE.setUTCDate( 11 );
  
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Fri Oct 11 2013 14:57:26 GMT+0800}
  ```
