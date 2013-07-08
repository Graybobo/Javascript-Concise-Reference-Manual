## decodeURIComponent() 函数:

decodeURIComponent() -- 对 encodeURIComponent 函数编码的 URI 进行解码

### decodeURIComponent() 语法:

  ```javascript
  decodeURIComponent( URIstring );
  ```

### decodeURIComponent() 函数参数说明:

URIstring -- 字符串，含有编码 URI 组件或其他要解码的文本。

### decodeURIComponent() 函数返回值:

URIstring 的副本，其中的十六进制转义序列将被它们表示的字符替换。

###### 示例:

  ```javascript
  var s = "https://github.com/Graybobo",
      s = encodeURIComponent( s );
  console.log( s );
  console.log( decodeURIComponent( s ) );
  ```

###### 结果:

  ```javascript
  >>> var s = "https://github.com/Graybobo", s = ...g( s ); console.log( decodeURIComponent( s ) );
  https%3A%2F%2Fgithub.com%2FGraybobo
  https://github.com/Graybobo
  ```
