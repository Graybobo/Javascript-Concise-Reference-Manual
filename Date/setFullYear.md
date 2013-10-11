#### setFullYear() 方法

  设置年份

##### 语法:

  ```javascript
  dateObject.setFullYear( year, month, day )
  ```

##### 参数说明:

  - year -- 必需。表示年份的四位整数。用本地时间表示。
  - month -- 可选。表示月份的数值，介于 0 ~ 11 之间。用本地时间表示。
  - day -- 可选。表示月中某一天的数值，介于 1 ~ 31 之间。用本地时间表示。

##### 返回值:

  返回调整过的日期的毫秒表示。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE );
  
  DATE.setFullYear( 2014 );
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Fri Oct 11 2013 14:40:29 GMT+0800}
  Date {Sat Oct 11 2014 14:40:29 GMT+0800}
  ```
