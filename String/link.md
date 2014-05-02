#### link 方法

  把字符串显示为超链接。

##### 语法:

  ```javascript
  stringObject.link( url );
  ```

#### 参数说明:

  url - 必需，要链接的 URL。

###### 示例:

  ```javascript
  var Str = "graybobo",
      s = Str.link( 'https://github.com/Graybobo' );
	  
  console.log( s );
  ```

###### 结果:

  ```javascript
  >>>
  <a href="https://github.com/Graybobo">graybobo</a>
  ```
