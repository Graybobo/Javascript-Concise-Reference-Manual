#### setTime() 方法

  以毫秒设置 Date 对象

##### 语法:

  ```javascript
  dateObject.setTime( millisec )
  ```

##### 参数说明:

  millisec -- 必需。要设置的日期和时间据 GMT 时间 1970 年 1 月 1 日午夜之间的毫秒数。这种类型的毫秒值可以传递给 Date() 构造函数，可以通过调用 Date.UTC() 和 Date.parse() 方法获得该值。以毫秒形式表示日期可以使它独立于时区。

##### 返回值:

  返回参数 millisec。在 ECMAScript 标准化之前，该方法不返回值。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();  
  DATE.setTime( 93771564221 );
  
  console.log( DATE );
  ```

###### 结果:

  ```javascript
  >>>
  Date {Thu Dec 21 1972 15:39:24 GMT+0800}
  ```
