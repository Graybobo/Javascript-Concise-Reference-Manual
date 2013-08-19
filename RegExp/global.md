#### global 属性

  RegExp 对象是否具有标志 g。

##### 定义和用法:

  - global 属性用于返回正则表达式是否具有标志 "g"。
  - 它声明了给定的正则表达式是否执行全局匹配。
  - 如果 g 标志被设置，则该属性为 true，否则为 false。

##### 语法:

  ```javascript
  RegExpObject.global
  ```
  
###### 示例:

  ```javascript
  var regexp1 = /(^\s*)|(\s*$)/,
      regexp2 = /(^\s*)|(\s*$)/g;
	  
  console.log( regexp1.global );
  console.log( regexp2.global );
  ```

###### 结果:

  ```javascript
  >>>
  false
  true
  ```
