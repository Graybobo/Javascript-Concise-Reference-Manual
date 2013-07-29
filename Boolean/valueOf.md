#### valueOf 方法

  valueOf() 返回 Boolean 对象的原始值。

##### 语法:

  ```javascript
  booleanObject.valueOf();
  ```

##### 返回值:

  booleanObject 的原始布尔值。

##### 异常抛出:

  如果调用该方法的对象不是 Boolean，则抛出异常 TypeError。
  
###### 示例:

  ```javascript
  var Bool = new Boolean( false );
  
  console.log( Bool.valueOf() );
  console.log( typeof ( Bool.valueOf() ) );
  ```

###### 结果:

  ```javascript
  >>>
  false
  boolean
  ```
