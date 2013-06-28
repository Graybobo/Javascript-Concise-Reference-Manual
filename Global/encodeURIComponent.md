## encodeURIComponent 函数:

encodeURIComponent -- 把字符串作为 URI 组件进行编码

### encodeURIComponent 语法:

  ```javascript
  encodeURIComponent( URIstring );
  ```

### encodeURIComponent 函数参数说明:

URIstring -- 字符串，含有 URI 组件或其他要编码的文本。

### encodeURIComponent 函数返回值:

URIstring 的副本，其中的某些字符将被十六进制的转义序列进行替换。

###### 示例:

  ```javascript
  var s = "https://github.com/Graybobo";
  console.log( encodeURIComponent( s ) );
  ```

###### 结果:

  ```javascript
  >>> var s = "https://github.com/Graybobo"; console.log( encodeURIComponent( s ) );
  https%3A%2F%2Fgithub.com%2FGraybobo
  ```
