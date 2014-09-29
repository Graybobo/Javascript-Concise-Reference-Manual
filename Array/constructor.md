#### constructor 属性

  constructor 属性返回对创建此对象的 Array 函数的引用。

##### 语法:

  ```javascript
  arrayObject.constructor
  ```

###### 示例:

  ```javascript
  var Arr = new Array();
  console.log( Arr.constructor );
  console.log( Arr.constructor == Array );
  ```

###### 结果:

  ```javascript
  >>>
  Array()
  true
  ```
