#### concat 方法

  连接两个或多个字符串。

##### 语法:

  ```javascript
  stringObject.concat( str, str, str, ... str );
  ```

##### 参数说明:

  str - 必需。将被连接为一个字符串的一个或多个字符串对象。

##### 说明:

  - concat() 方法将把它的所有参数转换成字符串，然后按顺序连接到字符串 stringObject 的尾部，并返回连接后的字符串。请注意，stringObject 本身并没有被更改。
  - stringObject.concat() 与 Array.concat() 很相似。

###### 示例:

  ```javascript
  var Str1 = "graybobo",
      Str2 = " long live",
      s = Str1.concat( Str2 );
	  
  console.log( s );
  ```

###### 结果:

  ```javascript
  >>>
  graybobo long live
  ```
