#### valueOf 方法

  返回 Array 对象的原始值。

##### 语法:

  ```javascript
  arrayObject.valueOf();
  ```

##### 返回值:

  arrayObject 的原始值。
  
##### 说明:

  - 原始值由 Array 对象派生的所有对象继承。
  - valueOf() 方法不创建新的数组，而是直接修改原有的数组。

##### 注:

  - 该方法会改变数组的长度。
  - valueOf() 方法通常由 JavaScript 在后台自动调用，并不显式地出现在代码中。

###### 示例:

  ```javascript
  var Arr = [11, 2, 73],
      a = Arr.valueOf();
  
  console.log( a );
  console.log( typeof a );
  ```

###### 结果:

  ```javascript
  >>>
  [11, 2, 73]
  object
  ```
