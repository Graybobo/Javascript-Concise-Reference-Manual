#### setYear() 方法

  设置年份

##### 语法:

  ```javascript
  dateObject.setYear( year )
  ```

##### 参数说明:

  year -- 表示年份的两位或四位数字。

##### 返回值:

  调整过的日期的毫秒表示。在 ECMAScript 标准化之前，该方法什么都不返回。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 如果 year 参数是两位的数字，比如 setYear(91)，则该方法会理解为 1991。如果要规定 1990 年之前或 1999 年之后的年份，请使用四位数字。

##### 注:

  从 ECMAScript v3 起，JavaScript 实现不再要求使用该函数，而使用 setFullYear() 函数代替它。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE );
  
  DATE.setYear( 14 );
  console.log( DATE );
  
  DATE.setYear( 2014 );
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Sun Oct 13 2013 11:15:42 GMT+0800}
  Date {Tue Oct 13 1914 11:15:42 GMT+0800}
  Date {Mon Oct 13 2014 11:15:42 GMT+0800}
  ```
