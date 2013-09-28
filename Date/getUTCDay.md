#### getUTCDay() 方法

  根据世界时返回表示星期的一天的一个数字。

##### 语法:

  ```javascript
  dateObject.getUTCDay();
  ```

##### 返回值:

  dateObject 用世界时表示时，返回该星期中的某一天 ，该值是 0( 星期天 ) ~ 6( 星期六 ) 中的一个值。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getUTCDay() );
  ```

###### 结果:

  ```javascript
  >>>
  6
  ```
