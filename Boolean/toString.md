#### toString 方法

  toString() 把逻辑值转换为字符串，并返回结果。

##### 语法:

  ```javascript
  booleanObject.toString();
  ```

##### 返回值:

  根据原始布尔值或者 booleanObject 对象的值返回字符串 "true" 或 "false"。

##### 异常抛出:

  如果调用该方法的对象不是 Boolean，则抛出异常 TypeError。

##### 注:

  在 Boolean 对象被用于字符串环境中时，此方法会被自动调用。
  
###### 示例:

  ```javascript
  var Bool = new Boolean( false ),
      s = Bool.toString();
	  
  console.log( s );
  console.log( typeof s );
  ```

###### 结果:

  ```javascript
  >>>
  false
  string
  ```
