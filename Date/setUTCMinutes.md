#### setUTCMinutes() 方法

  根据世界时( UTC )来设置指定时间的分钟

##### 语法:

  ```javascript
  dateObject.setUTCMinutes( min, sec, millisec )
  ```

##### 参数说明:

  - min -- 必需。要给 dateObject 设置的分钟字段的值，用世界时表示。该参数应该是 0 ~ 59 之间的整数。
  - sec -- 可选。要给 dateObject 设置的秒字段的值。使用世界时表示。该参数是 0 ~ 59 之间的整数。
  - millisec -- 可选。要给 dateObject 设置的毫秒字段的值。使用世界时表示。该参数是 0 ~ 999 之间的整数。

##### 返回值:

  调整过的日期的毫秒表示。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 如果上面的参数之一使用一位的数字来规定，那么 JavaScript 会在结果中加一或两个前置 0。

###### 示例:

  ```javascript
  var DATE = new Date();  
  DATE.setUTCMinutes( 2 );
  
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Tue Nov 12 2013 14:02:20 GMT+0800}
  ```
