#### localeCompare 方法

  用本地特定的顺序来比较两个字符串。

##### 语法:

  ```javascript
  stringObject.localeCompare( target );
  ```

##### 参数说明:

  target - 要以本地特定的顺序与 stringObject 进行比较的字符串。

##### 返回值:

  说明比较结果的数字。如果 stringObject 小于 target，则 localeCompare() 返回小于 0 的数。如果 stringObject 大于 target，则该方法返回大于 0 的数。如果两个字符串相等，或根据本地排序规则没有区别，该方法返回 0。
  
##### 说明:

  - 把 < 和 > 运算符应用到字符串时，它们只用字符的 Unicode 编码比较字符串，而不考虑当地的排序规则。以这种方法生成的顺序不一定是正确的。例如，在西班牙语中，其中字符 “ch” 通常作为出现在字母 “c” 和 “d” 之间的字符来排序。
  - localeCompare() 方法提供的比较字符串的方法，考虑了默认的本地排序规则。ECMAscript 标准并没有规定如何进行本地特定的比较操作，它只规定该函数采用底层操作系统提供的排序规则。

###### 示例:

  ```javascript
  var Str = "graybobo";
	  
  console.log( Str.localeCompare( 'b' ) );
  ```

###### 结果:

  ```javascript
  >>>
  1
  ```
