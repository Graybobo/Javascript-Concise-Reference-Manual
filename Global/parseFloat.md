#### Javascript parseFloat() 函数

  parseFloat() -- 解析一个字符串，并返回一个浮点数。
  
  该函数指定字符串中的首个字符是否是数字。如果是，则对字符串进行解析，直到到达数字的末端为止，然后以数字返回该数字，而不是作为字符串。

##### 语法:

  ```javascript
  parseFloat( string );
  ```

##### 参数说明:

  string -- 待解析的字符串。

##### 返回值:

  返回解析后的数字。

##### 说明:

  parseFloat 将它的字符串参数解析成为浮点数并返回。如果在解析过程中遇到了正负号（+ 或 -）、数字 (0-9)、小数点，或者科学记数法中的指数（e 或 E）以外的字符，则它会忽略该字符以及之后的所有字符，返回当前已经解析到的浮点数。同时参数字符串首位的空白符会被忽略。
  
 如果参数字符串的第一个字符不能被解析成为数字，则 parseFloat 返回 NaN。

##### 注:

  - 开头和结尾的空格是允许的。
  - 如果字符串的第一个字符不能被转换为数字，那么 parseFloat() 会返回 NaN。

###### 示例:

  ```javascript
  console.log( parseFloat( "100" ) );
  console.log( parseFloat( "77.00" ) );
  console.log( parseFloat( "100.91" ) );
  console.log( parseFloat( "100 200 300" ) );
  console.log( parseFloat( " 100 " ) );
  console.log( parseFloat( "18 year old girl" ) );
  console.log( parseFloat( "girl 18 years old" ) );
  ```

###### 结果:

  ```javascript
  >>>
  100
  77
  100.91
  100
  100
  18
  NaN
  ```
