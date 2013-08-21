#### lastIndex 属性

  一个整数，标示开始下一次匹配的字符位置。

##### 定义和用法:

  lastIndex 属性用于规定下次匹配的起始位置。

##### 语法:

  ```javascript
  RegExpObject.lastIndex
  ```

##### 说明:

  - 该属性存放一个整数，它声明的是上一次匹配文本之后的第一个字符的位置。
  - 上次匹配的结果是由方法 RegExp.exec() 和 RegExp.test() 找到的，它们都以 lastIndex 属性所指的位置作为下次检索的起始点。这样，就可以通过反复调用这两个方法来遍历一个字符串中的所有匹配文本。
  - 该属性是可读可写的。只要目标字符串的下一次搜索开始，就可以对它进行设置。当方法 exec() 或 test() 再也找不到可以匹配的文本时，它们会自动把 lastIndex 属性重置为 0。

###### 注:

  - 不具有标志 g 和不表示全局模式的 RegExp 对象不能使用 lastIndex 属性。
  - 如果在成功地匹配了某个字符串之后就开始检索另一个新的字符串，需要手动地把这个属性设置为 0。

###### 示例:

  ```javascript
  var str = "Dema West Viva",
      regexp = new RegExp("e", "g");
  
  regexp.test( str );
  console.log( regexp.lastIndex );
  ```

###### 结果:

  ```javascript
  >>>
  2
  ```
