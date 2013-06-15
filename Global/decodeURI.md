## decodeURI 属性:

decodeURI -- 对 encodeURI 函数编码过的 URI 进行解码

### decodeURI 语法:

  ```javascript
  decodeURI( string );
  ```

### decodeURI 函数参数说明:

string -- 需要解码的字符串，含有要解码的 URI 或其他要解码的文本。

### decodeURI 函数返回值:

string 的副本，其中的十六进制转义序列将被它们表示的字符替换。

###### 示例:

  ```javascript
  var s = encodeURI( "江湖中的我有好多朋友" );
  console.log( s );
  console.log( decodeURI( s ) );
  ```

###### 结果:

  ```javascript
  >>> var s = encodeURI( "江湖中的我有好多朋友" ); console.log( s ); console.log( decodeURI( s ) );
  %E6%B1%9F%E6%B9%96%E4%B8%AD%E7%9A%84%E6%88%91%E6%9C%89%E5%A5%BD%E5%A4%9A%E6%9C%8B%E5%8F%8B
  江湖中的我有好多朋友
  ```
