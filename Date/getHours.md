#### getHours() 方法

  回时间的小时字段。

##### 语法:

  ```javascript
  dateObject.getHours();
  ```

##### 返回值:

  dateObject 的小时字段，以本地时间显示。返回值是 0 （午夜） 到 23 （晚上 11 点）之间的一个整数。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 由 getHours() 返回的值是一个两位的数字。不过返回值不总是两位的，如果该值小于 10，则仅返回一位数字。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getHours() );
  ```

###### 结果:

  ```javascript
  >>>
  11
  ```
