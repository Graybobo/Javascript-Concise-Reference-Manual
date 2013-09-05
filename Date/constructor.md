#### constructor 属性

  constructor 属性返回对创建此对象的 Date 函数的引用。

##### 语法:

  ```javascript
  DateObject.constructor
  ```

###### 示例:

  ```javascript
  var DATE = new Date();
  console.log( DATE.constructor );
  console.log( DATE.constructor == Date );
  ```

###### 结果:

  ```javascript
  >>>
  Date()
  true
  ```
