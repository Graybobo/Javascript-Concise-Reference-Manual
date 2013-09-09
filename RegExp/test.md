#### test() 方法

  用于检测一个字符串是否匹配某个模式。

##### 语法:

  ```javascript
  RegExpObject.test( string )
  ```

##### 参数说明:

  string - 要检索的字符串
  
##### 返回值:

  如果字符串 string 中含有与 RegExpObject 匹配的文本，则返回 true，否则返回 false。
  
##### 说明:

  调用 RegExp 对象 r 的 test() 方法，并为它传递字符串 s，与这个表示式是等价的：(r.exec(s) != null)。
