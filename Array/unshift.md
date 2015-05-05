#### unshift 方法

  向数组的开头添加一个或多个元素，并返回新的长度。

##### 语法:

  ```javascript
  arrayObject.unshift( e1, e2, e3, ... ex );
  ```

##### 参数说明:

  - e1 - 必需。向数组添加的第一个元素。
  - e2 - 可选。向数组添加的第二个元素。
  - ex - 可选。要添加若干个元素。

##### 返回值:

  arrayObject 的新长度。
  
##### 说明:

  - unshift() 方法将把它的参数插入 arrayObject 的头部，并将已经存在的元素顺次地移到较高的下标处，以便留出空间。该方法的第一个参数将成为数组的新元素 0，如果还有第二个参数，它将成为新的元素 1，以此类推。
  - unshift() 方法不创建新的数组，而是直接修改原有的数组。

##### 注:

  - 该方法会改变数组的长度。
  - unshift() 方法无法在 Internet Explorer 中正确地工作！

###### 示例:

  ```javascript
  var Arr = [11, 2, 73];
  
  console.log( Arr );
  console.log( Arr.length );
  
  Arr.unshift( 32, 12, 9 ); 

  console.log( Arr );
  console.log( Arr.length );
  ```

###### 结果:

  ```javascript
  >>>
  [11, 2, 73]
  3
  [32, 12, 9, 11, 2, 73]
  6
  ```
