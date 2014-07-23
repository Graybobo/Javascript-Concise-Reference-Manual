#### search 方法

  检索字符串中指定的子字符串或与正则表达式相匹配的子字符串。

##### 语法:

  ```javascript
  stringObject.search( sub_str );
  stringObject.search( regexp );
  ```

##### 参数说明:

  - sub_str/regexp - 要检索的子字符串或 RegExp 对象。( 要执行忽略大小写的检索 请追加标志 i )

##### 返回值:

  stringObject 中第一个与 sub_str 或 regexp 相匹配的子字符串的起始位置。
  
##### 说明:

  search() 方法不执行全局匹配，它将忽略标志 g。它同时忽略 regexp 的 lastIndex 属性，并且总是从字符串的开始进行检索，这意味着它总是返回 stringObject 的第一个匹配的位置。
  
##### 注:

  如果没有找到任何匹配的子串，则返回 -1。

###### 示例:

  ```javascript
  var Str = "Hello graybobo";
	  
  console.log( Str.search( "o" ) );
  ```

###### 结果:

  ```javascript
  >>>
  4
  ```
