## isNaN 函数:

isNaN -- 检查其参数是否是非数字值

### isNaN 语法:

  ```javascript
  isNaN( x );
  ```

### isNaN 参数说明:

x -- 要检测的值

### isNaN 函数返回值:

  如果 x 是特殊的非数字值 NaN（或者能被转换为这样的值），返回的值就是 true。如果 x 是其他值,则返回 false。

###### 示例:

  ```javascript
  console.log( isNaN( 7 ) );
  console.log( isNaN( -7 ) );
  console.log( isNaN( "KILLHAPPY" ) );
  console.log( isNaN( "20130708" ) );
  console.log( isNaN( "2013-07-08" ) );
  ```

###### 结果:

  ```javascript
  >>> console.log( isNaN( 7 ) ); ... console.log( isNaN( "2013-07-08" ) );
  false
  false
  true
  false
  true
  ```
