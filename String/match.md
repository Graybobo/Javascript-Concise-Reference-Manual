#### match 方法

  在字符串内检索指定的值或一个或多个正则表达式的匹配。

##### 语法:

  ```javascript
  stringObject.match( search_value );
  stringObject.match( regexp );
  ```

##### 参数说明:

  - search_value - 必需，规定要检索的字符串值。
  - regexp - 必需。规定要匹配的模式的 RegExp 对象。如果该参数不是 RegExp 对象，则需要首先把它传递给 RegExp 构造函数，将其转换为 RegExp 对象。

##### 返回值:

  存放匹配结果的数组。该数组的内容依赖于 regexp 是否具有全局标志 g。
  
##### 说明:

  match() 方法类似 indexOf() 和 lastIndexOf()，但是它返回指定的值，而不是字符串的位置。
  
  match() 方法将检索字符串 stringObject，以找到一个或多个与 regexp 匹配的文本。这个方法的行为在很大程度上有赖于 regexp 是否具有标志 g。
  
  如果 regexp 没有标志 g，那么 match() 方法就只能在 stringObject 中执行一次匹配。如果没有找到任何匹配的文本， match() 将返回 null。否则，它将返回一个数组，其中存放了与它找到的匹配文本有关的信息。该数组的第 0 个元素存放的是匹配文本，而其余的元素存放的是与正则表达式的子表达式匹配的文本。除了这些常规的数组元素之外，返回的数组还含有两个对象属性。index 属性声明的是匹配文本的起始字符在 stringObject 中的位置，input 属性声明的是对 stringObject 的引用。
  
  如果 regexp 具有标志 g，则 match() 方法将执行全局检索，找到 stringObject 中的所有匹配子字符串。若没有找到任何匹配的子串，则返回 null。如果找到了一个或多个匹配子串，则返回一个数组。不过全局匹配返回的数组的内容与前者大不相同，它的数组元素中存放的是 stringObject 中所有的匹配子串，而且也没有 index 属性或 input 属性。
  
##### 注:

  在全局检索模式下，match() 即不提供与子表达式匹配的文本的信息，也不声明每个匹配子串的位置。如果您需要这些全局检索的信息，可以使用 RegExp.exec()。

###### 示例:

  ```javascript
  var Str = "graybobo";
	  
  console.log( Str.match( "bobo" ) );
  ```

###### 结果:

  ```javascript
  >>>
  ["bobo"]
  ```
