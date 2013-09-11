#### getYear() 方法

  返回表示年份的两位或四位的数字。

##### 语法:

  ```javascript
  dateObject.getYear();
  ```

##### 返回值:

  返回 dateObject 对象的年份字段( 2 位或 4 位数字 )。

##### 说明:

  - 该方法总是结合一个 Date 对象来使用。
  - 由 getYear() 返回的值不总是 4 位的数字！对于介于 1900 与 1999 之间的年份，getYear() 方法仅返回两位数字。对于 1900 之前或 1999 之后的年份，则返回 4 位数字！
  
##### 注:

  从 ECMAScript v3 开始，JavaScript 的实现就不再使用该方法，而使用 getFullYear() 方法取而代之！

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.getYear() );
  ```

###### 结果:

  ```javascript
  >>>
  113
  ```
