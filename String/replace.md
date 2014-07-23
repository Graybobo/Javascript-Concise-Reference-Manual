#### replace 方法

  在字符串中用一些字符替换另一些字符，或替换一个与正则表达式匹配的子串。

##### 语法:

  ```javascript
  stringObject.replace( sub_str, replacement );
  stringObject.replace( regexp, replacement );
  ```

##### 参数说明:

  - sub_str/regexp - 必需，规定要替换的子字符串 或 要替换的模式的 RegExp 对象。 ( 如果该值是一个字符串，则将它作为要检索的直接量文本模式，而不是首先被转换为 RegExp 对象。 )
  - replacement - 必需。一个字符串值。规定了替换文本或生成替换文本的函数。

##### 返回值:

  一个新的字符串，是用 replacement 替换了 regexp 的第一次匹配或所有匹配之后得到的。
  
##### 说明:

  字符串 stringObject 的 replace() 方法执行的是查找并替换的操作。它将在 stringObject 中查找与 regexp 相匹配的子字符串，然后用 replacement 来替换这些子串。如果 regexp 具有全局标志 g，那么 replace() 方法将替换所有匹配的子串。否则，它只替换第一个匹配子串。
  
  replacement 可以是字符串，也可以是函数。如果它是字符串，那么每个匹配都将由字符串替换。但是 replacement 中的 $ 字符具有特定的含义。
  
##### 注:

  ECMAScript v3 规定，replace() 方法的参数 replacement 可以是函数而不是字符串。在这种情况下，每个匹配都调用该函数，它返回的字符串将作为替换文本使用。该函数的第一个参数是匹配模式的字符串。接下来的参数是与模式中的子表达式匹配的字符串，可以有 0 个或多个这样的参数。接下来的参数是一个整数，声明了匹配在 stringObject 中出现的位置。最后一个参数是 stringObject 本身。

###### 示例:

  ```javascript
  var Str = "Hello graybobo";
	  
  console.log( Str.replace( "graybobo", "KILLHAPPY" ) );
  ```

###### 结果:

  ```javascript
  >>>
  Hello KILLHAPPY
  ```
