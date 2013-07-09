#### Javascript escape() 函数

  escape() -- 对字符串进行编码，这样就可以在所有的计算机上读取该字符串。

##### 语法:

  ```javascript
  escape( string );
  ```

##### 参数说明:

  string -- 要被转义或编码的字符串

##### 返回值:

  已编码的 string 的副本。其中某些字符被替换成了十六进制的转义序列。

##### 说明:

  该方法不会对 ASCII 字母和数字进行编码，也不会对下面这些 ASCII 标点符号进行编码： * @ - _ + . / 。其他所有的字符都会被转义序列替换。

##### 注:

  ECMAScript v3 反对使用该方法，应用使用 decodeURI() 和 decodeURIComponent() 替代它。

###### 示例:

  ```javascript
  console.log( escape( "Beautiful Girl!" ) );
  console.log( escape( "?!=()#%&" ) );
  ```

###### 结果:

  ```javascript
  >>>
  Beautiful%20Girl%21
  %3F%21%3D%28%29%23%25%26
  ```
