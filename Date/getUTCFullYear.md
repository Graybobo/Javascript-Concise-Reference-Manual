#### getUTCFullYear() 方法

  返回根据世界时( UTC )表示的年份的四位数字。

##### 语法:

  ```javascript
  dateObject.getUTCFullYear();
  ```

##### 返回值:

  返回 dateObject 用世界时表示时的年份，该值是一个四位的整数，而不是两位数的缩写。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getUTCFullYear() );
  ```

###### 结果:

  ```javascript
  >>>
  2013
  ```
