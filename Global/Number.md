#### Javascript Number() 函数

  Number() -- 把对象的值转换为数字

##### 语法:

  ```javascript
  Number( object );
  ```

##### 参数说明:

  object -- JavaScript 对象

##### 返回值:

  - 如果参数是 Date 对象，Number() 返回从 1970 年 1 月 1 日至今的毫秒数。
  - 如果对象的值能够转换为数字，则返回对应的 Number 类型值。
  - 如果对象的值无法转换为数字，那么 Number() 函数返回 NaN。
  - Boolean 类型返回 1 或 0。

###### 示例:

  ```javascript
  var obj_1 = new Date(),
      obj_2 = "1234567",
      obj_3 = "KILLHAPPY",
      obj_4 = new Boolean( true ),
      obj_5 = new Boolean( false );

  console.log( Number( obj_1 ) );
  console.log( Number( obj_2 ) );
  console.log( Number( obj_3 ) );
  console.log( Number( obj_4 ) );
  console.log( Number( obj_5 ) );
  ```

###### 结果:

  ```javascript
  >>>
  1373254928703
  1234567
  NaN
  1
  0
  ```
