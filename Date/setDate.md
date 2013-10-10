#### setDate() 方法

  设置月份的某一天

##### 语法:

  ```javascript
  dateObject.setDate( day )
  ```

##### 参数说明:

  day -- 表示一个月中的一天的一个数值( 1 ~ 31 )

##### 返回值:

  调整过的日期的毫秒表示。在 ECMAScript 标准化之前，该方法什么都不返回。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE );
  
  DATE.setDate( 18 );
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Thu Oct 10 2013 11:46:39 GMT+0800}
  Date {Fri Oct 18 2013 11:46:39 GMT+0800}
  ```
