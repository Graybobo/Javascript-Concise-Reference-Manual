#### constructor 属性

  constructor 属性返回对创建此对象的 String 函数的引用。

##### 语法:

  ```javascript
  stringObject.constructor
  ```

###### 示例:

  ```javascript
  var Str = new String();
  console.log( Str.constructor );
  console.log( Str.constructor == String );
  ```

###### 结果:

  ```javascript
  >>>
  String()
  true
  ```
