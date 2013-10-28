#### setMilliseconds() 方法

  设置时间的毫秒

##### 语法:

  ```javascript
  dateObject.setMilliseconds( millisec )
  ```

##### 参数说明:

  millisec -- 必需。用于设置 dateObject 毫秒字段，该参数是介于 0 ~ 999 之间的整数。

##### 返回值:

  调整过的日期的毫秒表示。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 如果上面的参数之一使用一位的数字来规定，那么 JavaScript 会在结果中加一或两个前置 0。

###### 示例:

  ```javascript
  var DATE = new Date();  
  DATE.setMilliseconds( 800 );
  
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Mon Oct 28 2013 14:53:13 GMT+0800}
  ```
