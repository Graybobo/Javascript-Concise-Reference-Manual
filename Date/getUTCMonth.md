#### getUTCMonth() 方法

  根据世界时返回一个表示月份的数字。

##### 语法:

  ```javascript
  dateObject.getUTCMonth();
  ```

##### 返回值:

  - 返回 dateObject 用世界时表示时的月份，该值是 0( 一月 ) ~ 11( 十二月 ) 之间中的一个整数。
  - 需要注意的是，Date 对象使用 1 来表示月的第一天，而不是像月份字段那样使用 0 来代表一年的第一个月。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getUTCMonth() );
  ```

###### 结果:

  ```javascript
  >>>
  8
  ```
