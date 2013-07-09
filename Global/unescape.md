#### Javascript unescape() 函数

  unescape() -- 对通过 escape() 编码的字符串进行解码。

##### 语法:

  ```javascript
  unescape( string );
  ```

##### 参数说明:

  string -- 要解码或反转义的字符串

##### 返回值:

  string 被解码后的一个副本。

##### 说明:

  该函数的工作原理是这样的：通过找到形式为 %xx 和 %uxxxx 的字符序列（x 表示十六进制的数字），用 Unicode 字符 \u00xx 和 \uxxxx 替换这样的字符序列进行解码。

##### 注:

  ECMAScript v3 已从标准中删除了 unescape() 函数，并反对使用它，因此应该用 decodeURI() 和 decodeURIComponent() 取而代之。

###### 示例:

  ```javascript
  var str = escape( "Beautiful Girl!" );
  console.log( str );
  console.log( unescape( str ) );
  ```

###### 结果:

  ```javascript
  >>>
  Beautiful%20Girl%21
  Beautiful Girl!
  ```
