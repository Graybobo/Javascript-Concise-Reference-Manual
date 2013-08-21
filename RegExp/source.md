#### source 属性

  正则表达式的源文本。

##### 定义和用法:

  - source 属性用于返回模式匹配所用的文本。
  - 该文本不包括正则表达式直接量使用的定界符，也不包括标志 g、i、m。

##### 语法:

  ```javascript
  RegExpObject.source
  ```

###### 示例:

  ```javascript
  var regexp = /(^\s*)|(\s*$)/g;
  
  console.log( regexp.source );
  ```

###### 结果:

  ```javascript
  >>>
  (^\s*)|(\s*$)
  ```
