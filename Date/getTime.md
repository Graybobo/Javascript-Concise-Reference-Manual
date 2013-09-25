#### getTime() 方法

  返回距 1970 年 1 月 1 日之间的毫秒数。

##### 语法:

  ```javascript
  dateObject.getTime();
  ```

##### 返回值:

  dateObject 指定的日期和时间距 1970 年 1 月 1 日午夜( GMT 时间 )之间的毫秒数。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getTime() );
  ```

###### 结果:

  ```javascript
  >>>
  1380073985263
  ```
