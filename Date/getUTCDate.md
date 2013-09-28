#### getUTCDate() 方法

  根据世界时返回一个月 (UTC) 中的某一天。

##### 语法:

  ```javascript
  dateObject.getUTCDate();
  ```

##### 返回值:

  dateObject 用世界时表示时，返回该月中的某一天( 是 1 ~ 31 中的一个值 )。

##### 说明:

  该方法总是结合一个 Date 对象来使用。

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getUTCDate() );
  ```

###### 结果:

  ```javascript
  >>>
  28
  ```
