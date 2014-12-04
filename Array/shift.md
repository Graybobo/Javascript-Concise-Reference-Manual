#### shift 方法

  删除并返回数组的第一个元素。

##### 语法:

  ```javascript
  arrayObject.shift();
  ```

##### 返回值:

  数组中第一个元素的值。
  
##### 说明:

  如果数组是空的，那么 shift() 方法将不进行任何操作，返回 undefined 值。该方法不创建新数组，而是直接修改原有的 arrayObject。

##### 注:

  该方法会改变数组的长度。

###### 示例:

  ```javascript
  var Arr = [1, 2, 3, 4, 5, 6];
	  
  console.log( Arr.shift() );
  console.log( Arr );
  ```

###### 结果:

  ```javascript
  >>>
  1
  [2, 3, 4, 5, 6]
  ```
