#### UTC 方法

  可根据世界时返回 1970 年 1 月 1 日 到指定日期的毫秒数。

##### 语法:

  ```javascript
  dateObject.UTC( year, month, day, hours, minutes, seconds, ms );
  ```

##### 参数说明:

  - year -- 必需。表示年份的四位数字。
  - month -- 必需。表示月份的整数，介于 0 ~ 11。
  - day -- 必需。表示日期的整数，介于 1 ~ 31。
  - hours -- 可选。表示小时的整数，介于 0 ~ 23。
  - minutes -- 可选。表示分钟的整数，介于 0 ~ 59。
  - seconds -- 可选。表示秒的整数，介于 0 ~ 59。
  - ms -- 可选。表示毫秒的整数，介于 0 ~ 999。

##### 返回值:

  返回指定的时间距 GMT 时间 1970 年 1 月 1 日午夜的毫秒数。

##### 说明:

  - Date.UTC() 是一种静态方法，因为需要使用构造函数 Date() 来调用它，而不是通过某个 Date 对象调用。
  - Date.UTC() 方法的参数指定日期和时间，它们都是 UTC 时间，处于 GMT 时区。指定的 UTC 时间将转换成毫秒的形式，这样构造函数 Date() 和方法 Date.setTime() 就可以使用它了。
  
###### 示例:

  ```javascript
  var DATE = Date.UTC( 2005, 11, 20 );  

  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  1135036800000
  ```
