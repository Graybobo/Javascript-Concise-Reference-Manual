## String() 函数

String() -- 把对象的值转换为字符串

### String() 语法:

  ```javascript
  String( object );
  ```

### String() 参数说明:

object -- JavaScript 对象

### String() 函数返回值:

  返回 object 的 String 类型值。

###### 示例:

  ```javascript
  var obj_1 = new Date(),
      obj_2 = 1234567,
      obj_3 = "KILLHAPPY",
      obj_4 = new Boolean( true ),
      obj_5 = new Boolean( false ),
      obj_6 = new Boolean( 1 ),
      obj_7 = new Boolean( 0 );

  console.log( String( obj_1 ) );
  console.log( String( obj_2 ) );
  console.log( String( obj_3 ) );
  console.log( String( obj_4 ) );
  console.log( String( obj_5 ) );
  console.log( String( obj_6 ) );
  console.log( String( obj_7 ) );
  ```

###### 结果:

  ```javascript
  >>> ......
  Mon Jul 08 2013 11:50:45 GMT+0800
  1234567
  KILLHAPPY
  true
  false
  true
  false
  ```
