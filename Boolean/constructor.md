#### Boolean constructor 属性

  constructor 属性返回对创建此对象的 Boolean 函数的引用。

##### 语法:

  ```javascript
  booleanObject.constructor
  ```

###### 示例:

  ```javascript
  var Bool = new Boolean();
  console.log( Bool.constructor );
  console.log( Bool.constructor == Boolean );
  ```

###### 结果:

  ```javascript
  >>>
  Boolean()
  true
  ```
