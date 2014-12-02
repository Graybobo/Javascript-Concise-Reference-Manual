#### push 方法

  向数组的尾部添加元素，返回新的长度。

##### 语法:

  ```javascript
  arrayObject.push( e1, e2, e3, ... ex );
  ```

##### 参数说明:

  - e1 - 必需。要添加到数组的第一个元素。
  - e2/ex - 可选。要添加到数组的其他元素。

##### 返回值:

  把指定的值添加到数组后的新长度。
  
##### 说明:

  - push() 方法可把它的参数顺序添加到 arrayObject 的尾部。它直接修改 arrayObject，而不是创建一个新的数组。
  - push() 方法和 pop() 方法使用数组提供的先进后出栈的功能。

##### 注:

  该方法会改变数组的长度。

###### 示例:

  ```javascript
  var Arr = [1, 2, 3];
	  
  console.log( Arr.push( 4, 5, 6 ) );
  console.log( Arr );
  ```

###### 结果:

  ```javascript
  >>>
  6
  [1, 2, 3, 4, 5, 6]
  ```
