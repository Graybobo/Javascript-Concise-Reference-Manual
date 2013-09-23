#### getSeconds() 方法

  返回时间的秒数。

##### 语法:

  ```javascript
  dateObject.getSeconds();
  ```

##### 返回值:

  dateObject 的秒字段，以本地时间显示。返回值是 0 ~ 59 之间的一个整数。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 由 getSeconds() 返回的值是一个两位的数字。不过返回值不总是两位的，如果该值小于 10，则仅返回一位数字。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getSeconds() );
  ```

###### 结果:

  ```javascript
  >>>
  14
  ```
