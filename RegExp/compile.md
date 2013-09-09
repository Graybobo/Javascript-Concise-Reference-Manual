#### compile() 方法

  - compile() 方法用于在脚本执行过程中编译正则表达式。
  - compile() 方法也可用于改变和重新编译正则表达式。

##### 语法:

  ```javascript
  RegExpObject.compile( regexp, modifier )
  ```

##### 参数说明:

  - regexp: 正则表达式。
  - modifier: 规定匹配的类型。"g" 用于全局匹配，"i" 用于区分大小写，"gi" 用于全局区分大小写的匹配。
