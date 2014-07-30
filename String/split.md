#### split 方法

  将字符串分割成字符串数组。

##### 语法:

  ```javascript
  stringObject.split( separator, howmany );
  ```

##### 参数说明:

  - separator - 必需。字符串或正则表达式，从该参数指定的地方分割 stringObject。
  - howmany - 可选。该参数可指定返回的数组的最大长度。如果设置了该参数，返回的子串不会多于这个参数指定的数组。如果没有设置该参数，整个字符串都会被分割，不考虑它的长度。

##### 返回值:

  一个字符串数组。该数组是通过在 separator 指定的边界处将字符串 stringObject 分割成子串创建的。返回的数组中的字串不包括 separator 自身。但是，如果 separator 是包含子表达式的正则表达式，那么返回的数组中包括与这些子表达式匹配的字串（但不包括与整个正则表达式匹配的文本）。
  
##### 注:

  - 如果把空字符串 ("") 用作 separator，那么 stringObject 中的每个字符之间都会被分割。
  - String.split() 执行的操作与 Array.join 执行的操作是相反的。

###### 示例:

  ```javascript
  var Str = "K I L L H A P P Y";
	  
  console.log( Str.split( " " ) );
  ```

###### 结果:

  ```javascript
  >>>
  ["K", "I", "L", "L", "H", "A", "P", "P", "Y"]
  ```
