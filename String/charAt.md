#### charAt 方法

  返回指定位置的字符。

##### 语法:

  ```javascript
  stringObject.charAt( index );
  ```

##### 参数说明:

  index - 必需。表示字符串中某个位置的数字，即字符在字符串中的下标。
  
##### 返回值:

  JavaScript 并没有一种有别于字符串类型的字符数据类型，所以返回的字符是长度为 1 的字符串。

##### 说明:

  字符串中第一个字符的下标是 0。如果参数 index 不在 0 与 string.length 之间，该方法将返回一个空字符串。

###### 示例:

  ```javascript
  var Str = "graybobo",
      s = Str.charAt( 3 );
	  
  console.log( s );
  ```

###### 结果:

  ```javascript
  >>>
  y
  ```
