#### concat 方法

  连接两个或多个数组。

##### 语法:

  ```javascript
  arrayObject.concat( Array2, Array3, ...... ArrayN );
  ```

##### 参数说明:

  - ArrayN - 必需。该参数可以是具体的值，也可以是数组对象。可以是任意多个。

##### 返回值:

  返回一个新的数组。该数组是通过把所有 arrayX 参数添加到 arrayObject 中生成的。如果要进行 concat()操作的参数是数组，那么添加的是数组中的元素，而不是数组。
  
##### 说明:

  该方法不会改变现有的数组，而仅仅会返回被连接数组的一个副本。

###### 示例:

  ```javascript
  var Arr = [1, 2, 3],
      Arr2 = [4, 5, 6];
	  
  console.log( Arr.concat( 4, 5, 6 ) );
  console.log( Arr.concat( Arr2 ) );
  ```

###### 结果:

  ```javascript
  >>>
  [1, 2, 3, 4, 5, 6]
  [1, 2, 3, 4, 5, 6]
  ```
