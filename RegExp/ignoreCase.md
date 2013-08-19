#### ignoreCase 属性

  RegExp 对象是否具有标志 i。

##### 定义和用法:

  - ignoreCase 属性规定是否设置 "i" 标志。
  - 如果设置了 "i" 标志，则返回 true，否则返回 false。

##### 语法:

  ```javascript
  RegExpObject.ignoreCase
  ```
  
###### 示例:

  ```javascript
  var regexp = /^[-a-z.-@,'s]*$/i;	  
  console.log( regexp.ignoreCase );
  ```

###### 结果:

  ```javascript
  >>>
  true
  ```
