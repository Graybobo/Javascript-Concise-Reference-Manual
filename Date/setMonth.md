#### setMonth() 方法

  设置月份

##### 语法:

  ```javascript
  dateObject.setMonth( month, day )
  ```

##### 参数说明:

  - month -- 必需。一个表示月份的数值，该值介于 0（一月） ~ 11（十二月） 之间。
  - day -- 可选。一个表示月的某一天的数值，该值介于 1 ~ 31 之间（以本地时间计）。[ 在 EMCAScript 标准化之前，不支持该参数。 ]

##### 返回值:

  调整过的日期的毫秒表示。在 ECMAScript 标准化之前，该方法什么都不返回。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE );
  
  DATE.setMonth( 11 );
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Fri Oct 11 2013 14:34:28 GMT+0800}
  Date {Wed Dec 11 2013 14:34:28 GMT+0800}
  ```
