#### setMinutes() 方法

  设置时间的分钟字段

##### 语法:

  ```javascript
  dateObject.setMinutes( min, sec, millisec )
  ```

##### 参数说明:

  - min -- 必需。表示分钟的数值，介于 0 ~ 59 之间，以本地时间计( 下同 )。
  - sec -- 可选。表示秒的数值，介于 0 ~ 59 之间。( 在 EMCAScript 标准化之前，不支持该参数。)
  - millisec -- 可选。表示毫秒的数值，介于 0 ~ 999 之间。( 在 EMCAScript 标准化之前，不支持该参数。)

##### 返回值:

  调整过的日期的毫秒表示。在 ECMAScript 标准化之前，该方法什么都不返回。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 如果上面的参数之一使用一位的数字来规定，那么 JavaScript 会在结果中加一或两个前置 0。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE );
  
  DATE.setMinutes( 11 );
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Mon Oct 14 2013 20:40:08 GMT+0800}
  Date {Mon Oct 14 2013 20:11:08 GMT+0800}
  ```
