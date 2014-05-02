#### lastIndexOf 方法

  在一个字符串中的指定位置从后向前搜索，返回指定的字符串值最后出现的位置。

##### 语法:

  ```javascript
  stringObject.lastIndexOf( search_value, from_index );
  ```

##### 参数说明:

  search_value - 必需。规定需检索的字符串值。
  from_index - 可选的整数参数。规定在字符串中开始检索的位置。它的合法取值是 0 到 stringObject.length - 1。如省略该参数，则将从字符串的最后一个字符处开始检索。

##### 返回值:

  如果在 stringObject 中的 fromindex 位置之前存在 searchvalue，则返回的是出现的最后一个 searchvalue 的位置。
  
##### 说明:

  - 该方法将从尾到头地检索字符串 stringObject，看它是否含有子串 searchvalue。
  - 开始检索的位置在字符串的 fromindex 处或字符串的结尾（没有指定 fromindex 时）。
  - 如果找到一个 searchvalue，则返回 searchvalue 的第一个字符在 stringObject 中的位置。
  - stringObject 中的字符位置是从 0 开始的。
  - lastIndexOf() 方法对大小写敏感！
  - 如果要检索的字符串值没有出现，则该方法返回 -1。

###### 示例:

  ```javascript
  var Str = "graybobo",
      s = Str.lastIndexOf( 'b' );
	  
  console.log( s );
  ```

###### 结果:

  ```javascript
  >>>
  6
  ```
