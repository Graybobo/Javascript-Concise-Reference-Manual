#### Javascript parseInt() 函数

  parseInt() -- 解析一个字符串，并返回一个整数。

##### 语法:

  ```javascript
  parseInt( string, radix );
  ```

##### 参数说明:

  - string -- 待解析的字符串
  - radix -- 可选。表示要解析的数字的基数。该值介于 2 ~ 36 之间。如果省略该参数或其值为 0，则数字将以 10 为基础来解析。如果它以 "0x" 或 "0X" 开头，将以 16 为基数。如果该参数小于 2 或者大于 36，则 parseInt() 将返回 NaN。

##### 返回值:

  返回解析后的数字( 整数 )。

##### 说明:

  当参数 radix 的值为 0，或没有设置该参数时，parseInt() 会根据 string 来判断数字的基数。
  
  举例，如果 string 以 "0x" 开头，parseInt() 会把 string 的其余部分解析为十六进制的整数。如果 string 以 0 开头，那么 ECMAScript v3 允许 parseInt() 的一个实现把其后的字符解析为八进制或十六进制的数字。如果 string 以 1 ~ 9 的数字开头，parseInt() 将把它解析为十进制的整数。

##### 注:

  - 只有字符串中的第一个数字会被返回。
  - 开头和结尾的空格是允许的。
  - 如果字符串的第一个字符不能被转换为数字，那么 parseFloat() 会返回 NaN。

###### 示例:

  ```javascript
  console.log( parseInt( "100" ) );
  console.log( parseInt( "23", 10 ) );
  console.log( parseInt( "14", 2 ) );
  console.log( parseInt( "19", 8 ) );
  console.log( parseInt( "X0", 16 ) );
  console.log( parseInt( "008" ) );
  console.log( parseInt( "N001" ) );
  ```

###### 结果:

  ```javascript
  >>>
  100
  23
  1
  1
  NaN
  8
  NaN
  ```
