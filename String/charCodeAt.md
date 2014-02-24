#### charCodeAt 方法

  返回指定位置的字符的 Unicode 编码。这个返回值是 0 - 65535 之间的整数。

##### 语法:

  ```javascript
  stringObject.charCodeAt( index );
  ```

##### 参数说明:

  index - 必需。表示字符串中某个位置的数字，即字符在字符串中的下标。

##### 说明:

  - 字符串中第一个字符的下标是 0。如果参数 index 不在 0 与 string.length 之间，该方法将返回一个空字符串。
  - 方法 charCodeAt() 与 charAt() 方法执行的操作相似，只不过前者返回的是位于指定位置的字符的编码，而后者返回的是字符子串。

###### 示例:

  ```javascript
  var Str = "graybobo",
      s = Str.charCodeAt( 6 );
	  
  console.log( s );
  ```

###### 结果:

  ```javascript
  >>>
  98
  ```
