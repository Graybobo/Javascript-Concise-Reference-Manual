#### setUTCFullYear() 方法

  根据世界时( UTC )设置年份

##### 语法:

  ```javascript
  dateObject.setUTCFullYear( year, month, day )
  ```

##### 参数说明:

  - year -- 必需。要给 dateObject 设置的年份字段的值。该参数应该是含有世纪值的完整年份，如 1999，而不只是缩写的年份值，比如 99。
  - month -- 可选。要给 dateObject 设置的月份字段的值。使用世界时表示。该参数是 0 ~ 11 之间的整数。
  - day -- 可选。要给 dateObject 设置的天字段的值。使用世界时表示。该参数是 1 ~ 31 之间的整数。

##### 返回值:

  调整过的日期的毫秒表示。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();  
  DATE.setUTCFullYear( 2000 );
  
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Sat Nov 11 2000 11:00:28 GMT+0800}
  ```
