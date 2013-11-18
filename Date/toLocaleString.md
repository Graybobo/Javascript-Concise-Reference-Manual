#### toLocaleString 方法

  根据本地时间格式，把 Date 对象转换为字符串。

##### 语法:

  ```javascript
  dateObject.toLocaleString();
  ```

##### 返回值:

  dateObject 的字符串表示，以本地时间区表示，并根据本地规则格式化。
  
###### 示例:

  ```javascript
  var DATE = new Date();  

  console.log( DATE.toLocaleString() );
  ```

###### 结果:

  ```javascript
  >>>
  2013年11月18日 13:20:50
  ```
