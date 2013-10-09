#### getUTCMilliseconds() 方法

  根据世界时( UTC )返回时间的毫秒

##### 语法:

  ```javascript
  dateObject.getUTCMilliseconds();
  ```

##### 返回值:

  当 dateObject 用世界时表示时，返回它的毫秒字段，该值是一个 0 ~ 999 之间的整数。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 由 getUTCMilliseconds() 返回的值是一个三位的数字。不过返回值不总是三位的，如果该值小于 100，则仅返回两位数字，如果该值小于 10，则仅返回一位数字。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getUTCMilliseconds() );
  ```

###### 结果:

  ```javascript
  >>>
  916
  ```
