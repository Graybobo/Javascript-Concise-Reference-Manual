#### getUTCHours() 方法

  根据世界时( UTC )返回时间的小时

##### 语法:

  ```javascript
  dateObject.getUTCHours();
  ```

##### 返回值:

  返回 dateObject 用世界时表示时的小时字段，该值是一个 0（午夜） ~ 23（晚上 11 点） 之间的整数。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 由 getUTCHours() 返回的值是一个两位的数字。不过返回值不总是两位的，如果该值小于 10，则仅返回一位数字。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getUTCHours() );
  ```

###### 结果:

  ```javascript
  >>>
  3
  ```
