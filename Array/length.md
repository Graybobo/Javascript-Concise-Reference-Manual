#### length 方法

  设置或返回数组中元素的数目。

##### 语法:

  ```javascript
  arrayObject.length;
  arrayObject.length = n;
  ```

##### 说明:

  - 数组的 length 属性总是比数组中定义的最后一个元素的下标大 1。对于那些具有连续元素，而且以元素 0 开始的常规数组而言，属性 length 声明了数组中的元素的个数。
  - 数组的 length 属性在用构造函数 Array() 创建数组时被初始化。给数组添加新元素时，如果必要，将更新 length 的值。
  - 设置 length 属性可改变数组的大小。如果设置的值比其当前值小，数组将被截断，其尾部的元素将丢失。如果设置的值比它的当前值大，数组将增大，新的元素被添加到数组的尾部，它们的值为 undefined。

###### 示例:

  ```javascript
  var Arr = new Array();
  Arr[0] = 0;
  Arr[1] = 1;
  Arr[2] = 2;
  Arr[3] = 3;
  Arr[4] = 4;
	  
  console.log( Arr.length );

  Arr.length = 3;

  console.log( Arr );
  console.log( Arr.length );  
  ```

###### 结果:

  ```javascript
  >>>
  5
  [0, 1, 2]
  3
  ```
