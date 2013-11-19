#### toLocaleTimeString 方法

  toLocaleTimeString() 方法可根据本地时间把 Date 对象的时间部分转换为字符串，并返回结果。

##### 语法:

  ```javascript
  dateObject.toLocaleTimeString();
  ```

##### 返回值:

  dateObject 的时间部分的字符串表示，以本地时间区表示，并根据本地规则格式化。
  
###### 示例:

  ```javascript
  var DATE = new Date();  

  console.log( DATE.toLocaleTimeString() );
  ```

###### 结果:

  ```javascript
  >>>
  14:22:10
  ```
