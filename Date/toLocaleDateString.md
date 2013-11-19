#### toLocaleDateString 方法

  根据本地时间把 Date 对象的日期部分转换为字符串，并返回结果。

##### 语法:

  ```javascript
  dateObject.toLocaleDateString();
  ```

##### 返回值:

  dateObject 的日期部分的字符串表示，以本地时间区表示，并根据本地规则格式化。
  
###### 示例:

  ```javascript
  var DATE = new Date();  

  console.log( DATE.toLocaleDateString() );
  ```

###### 结果:

  ```javascript
  >>>
  2013年11月19日
  ```
