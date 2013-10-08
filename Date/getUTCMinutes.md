#### getUTCMinutes() 方法

  根据世界时( UTC )返回时间的分钟字段

##### 语法:

  ```javascript
  dateObject.getUTCMinutes();
  ```

##### 返回值:

  返回 dateObject 用世界时表示时的分钟字段，该值是一个 0 ~ 59 之间的整数。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 由 getUTCMinutes() 返回的值是一个两位的数字。不过返回值不总是两位的，如果该值小于 10，则仅返回一位数字。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getUTCMinutes() );
  ```

###### 结果:

  ```javascript
  >>>
  42
  ```
