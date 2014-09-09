#### substr 方法

  从起始索引位置提取字符串中指定数目的字符。

##### 语法:

  ```javascript
  stringObject.substr( start_index, length );
  ```

##### 参数说明:

  - start_index - 必需。要抽取的子串的起始下标。必须是数值。如果是负数，那么该参数声明从字符串的尾部开始算起的位置。也就是说，-1 指字符串中最后一个字符，-2 指倒数第二个字符，以此类推。
  - substrment - 可选。子串中的字符数。必须是数值。如果省略了该参数，那么返回从 stringObject 的开始位置到结尾的字串。

##### 返回值:

  一个新的字符串，包含从 stringObject 的 start（包括 start 所指的字符） 处开始的 length 个字符。如果没有指定 length，那么返回的字符串包含从 start 到 stringObject 的结尾的字符。
  
##### 说明:

  substr() 的参数指定的是子串的开始位置和长度，因此它可以替代 substring() 和 slice() 来使用。

##### 注:

  - ECMAscript 没有对该方法进行标准化，因此反对使用它。
  - 在 IE 4 中，参数 start 的值无效。在这个 BUG 中，start 规定的是第 0 个字符的位置。在之后的版本中，此 BUG 已被修正。

###### 示例:

  ```javascript
  var Str = "Hello KILLHAPPY";
	  
  console.log( Str.substr( 6, 9 ) );
  ```

###### 结果:

  ```javascript
  >>>
  KILLHAPPY
  ```
