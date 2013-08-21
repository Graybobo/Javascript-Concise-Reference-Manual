#### multiline 属性

  RegExp 对象是否具有标志 m。

##### 定义和用法:

  - multiline 属性用于返回正则表达式是否具有标志 m。
  - 它声明了给定的正则表达式是否以多行模式执行模式匹配。
  - 在这种模式中，如果要检索的字符串中含有换行符，^ 和 $ 锚除了匹配字符串的开头和结尾外还匹配每行的开头和结尾。
  - 如果 m 标志被设置，则该属性为 true，否则为 false。

##### 语法:

  ```javascript
  RegExpObject.multiline
  ```

###### 示例:

  ```javascript
  var regexp1 = new RegExp("reg", "m"),
      regexp2 = new RegExp("reg");
  
  console.log( regexp1.multiline );
  console.log( regexp2.multiline );
  ```

###### 结果:

  ```javascript
  >>>
  true
  false
  ```
