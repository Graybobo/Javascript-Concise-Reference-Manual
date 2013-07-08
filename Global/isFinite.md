## isFinite() 函数

isFinite() -- 检查其参数是否是无穷大

### isFinite() 语法:

  ```javascript
  isFinite( number );
  ```

### isFinite() 参数说明:

number -- 要检测的数字

### isFinite() 函数返回值:

  - 如果 number 是有限数字（或可转换为有限数字），那么返回 true。
  - 如果 number 是 NaN（非数字），或者是正、负无穷大的数，则返回 false。

###### 示例:

  ```javascript
  console.log( isFinite( 7 ) );
  console.log( isFinite( NaN ) );
  console.log( isFinite( Infinity ) );
  ```

###### 结果:

  ```javascript
  >>> console.log( isFinite( 7 ) ); console.log( isFinite( NaN ) ); console.log( isFinite( Infinity ) );
  true
  false
  false
  ```
