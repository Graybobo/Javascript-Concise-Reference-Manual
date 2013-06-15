## encodeURI 属性:

encodeURI -- 把字符串作为 URI 进行编码

### encodeURI 语法:

  ```javascript
  encodeURI( string );
  ```

### encodeURI 函数参数说明:

string -- 需要编码的字符串，含有 URI 或其他要编码的文本。

### encodeURI 函数返回值:

string 的副本，其中的某些字符将被十六进制的转义序列进行替换。

###### 示例:

  ```javascript
  var s = "江湖中的我有好多朋友";
  console.log( encodeURI( s ) );
  ```

###### 结果:

  ```javascript
  >>> var s = "江湖中的我有好多朋友"; console.log( encodeURI( s ) );
  %E6%B1%9F%E6%B9%96%E4%B8%AD%E7%9A%84%E6%88%91%E6%9C%89%E5%A5%BD%E5%A4%9A%E6%9C%8B%E5%8F%8B
  ```
