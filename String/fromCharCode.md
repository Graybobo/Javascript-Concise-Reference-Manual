#### fromCharCode 方法

  接受一个指定的 Unicode 值，然后返回一个字符串。

##### 语法:

  ```javascript
  String.fromCharCode( UnicodeNum, UnicodeNum, ..., UnicodeNum );
  ```

##### 参数说明:

  UnicodeNum - 必需。一个或多个 Unicode 值，即要创建的字符串中的字符的 Unicode 编码。

##### 说明:

  - 该方法是 String 的静态方法，字符串中的每个字符都由单独的数字 Unicode 编码指定。
  - 不能作为您已创建的 String 对象的方法来使用。因此它的语法应该是 String.fromCharCode()，而不是 stringObject.fromCharCode()。

###### 示例:

  ```javascript	  
  console.log( String.fromCharCode( 75, 73, 76, 76, 72, 65, 80, 80, 89 ) );
  ```

###### 结果:

  ```javascript
  >>>
  KILLHAPPY
  ```
