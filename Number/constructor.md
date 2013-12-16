#### constructor 属性

  constructor 属性返回对创建此对象的 Number 函数的引用。

##### 语法:

  ```javascript
  numberObject.constructor
  ```

###### 示例:

  ```javascript
  var Num = new Number();
  console.log( Num.constructor );
  console.log( Num.constructor == Number );
  ```

###### 结果:

  ```javascript
  >>>
  Number()
  true
  ```
