#### pop 方法

  删除并返回数组的最后一个元素。

##### 语法:

  ```javascript
  arrayObject.pop();
  ```

##### 返回值:

  arrayObject 的最后一个元素。
  
##### 说明:

  - pop() 方法将删除 arrayObject 的最后一个元素，把数组长度减 1，并且返回它删除的元素的值。
  - 如果数组已经为空，则 pop() 不改变数组，并返回 undefined 值。

###### 示例:

  ```javascript
  var Arr = [1, 2, 3, 4, 5, 6];
	  
  console.log( Arr.pop() );
  console.log( Arr.length );
  ```

###### 结果:

  ```javascript
  >>>
  6
  5
  ```
