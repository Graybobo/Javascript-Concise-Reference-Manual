#### setUTCHours() 方法

  根据世界时( UTC )设置小时( 0 - 23 )

##### 语法:

  ```javascript
  dateObject.setUTCHours( hour, min, sec, millisec )
  ```

##### 参数说明:

  - hour -- 必需。要给 dateObject 设置的小时字段的值。该参数是 0 ~ 23 之间的整数。
  - min -- 可选。要给 dateObject 设置的分钟字段的值。该参数是 0 ~ 59 之间的整数。
  - sec -- 可选。要给 dateObject 设置的秒字段的值。该参数是 0 ~ 59 之间的整数。
  - millisec -- 可选。要给 dateObject 设置的毫秒字段的值。该参数是 1 ~ 999 之间的整数。

##### 返回值:

  调整过的日期的毫秒表示。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 如果没有规定 min, sec 以及 millisec 参数，则使用从 getUTCMinutes, getUTCSeconds 以及 getUTCMilliseconds 方法返回的值。
  - 如果您规定的参数在指定范围之外，则 setUTCHours 尝试据此来更新 Date 对象中的日期信息。例如，如果 sec 参数的值是 100，则增加 1 分钟 (min + 1)，而秒数为 40。

###### 示例:

  ```javascript
  var DATE = new Date();  
  DATE.setUTCHours( 23 );
  
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Wed Nov 13 2013 07:47:35 GMT+0800}
  ```
