#### indexOf 方法

  检索某个指定的字符串值在字符串中首次出现的位置。

##### 语法:

  ```javascript
  stringObject.indexOf( search_value, from_index );
  ```

##### 参数说明:

  search_value - 必需。规定需检索的字符串值。
  from_index - 可选的整数参数。规定在字符串中开始检索的位置。它的合法取值是 0 到 stringObject.length - 1。如省略该参数，则将从字符串的首字符开始检索。

##### 说明:

  - stringObject 中的字符位置是从 0 开始的。
  - 该方法将从头到尾地检索字符串 stringObject，看它是否含有子串 searchvalue。开始检索的位置在字符串的 fromindex 处或字符串的开头（没有指定 fromindex 时）。如果找到一个 searchvalue，则返回 searchvalue 的第一次出现的位置。
  - 如果要检索的字符串值没有出现，则该方法返回 -1。

###### 示例:

  ```javascript
  var Str = "KILLHAPPY";	  
  
  console.log( Str.indexOf( "H" ) );
  ```

###### 结果:

  ```javascript
  >>>
  4
  ```
