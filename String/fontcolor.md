#### fontcolor 方法

  按照指定的颜色来显示字符串。

##### 语法:

  ```javascript
  stringObject.fontcolor( color );
  ```

##### 参数说明:

  color - 必需。为字符串规定 font-color。该值必须是颜色名(red)、RGB 值(rgb(255,0,0))或者十六进制数(#FF0000)。

###### 示例:

  ```javascript
  var Str = "graybobo",
      s = Str.fontcolor( '#0088DD' );
	  
  console.log( s );
  ```

###### 结果:

  ```javascript
  >>>
  <font color="#0088DD">graybobo</font>
  ```
