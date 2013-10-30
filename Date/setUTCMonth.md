#### setUTCMonth() 方法

  根据世界时( UTC )来设置月份

##### 语法:

  ```javascript
  dateObject.setUTCMonth( month, day )
  ```

##### 参数说明:

  - month -- 必需。要给 dateObject 设置的月份字段的值，用世界时表示。该参数是 0( 一月 ) ~ 11( 十二月 )之间的整数。
  - day -- 可选。在 1 ~ 31 之间的整数，用作 dateObject 的天字段，用世界时表示。

##### 返回值:

  调整过的日期的毫秒表示。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();  
  DATE.setUTCMonth( 2 );
  
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Sat Mar 30 2013 15:03:50 GMT+0800}
  ```
