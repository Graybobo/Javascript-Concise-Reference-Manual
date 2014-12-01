#### join 方法

  把数组的元素放入一个字符串，元素通过指定的分隔符进行分隔。

##### 语法:

  ```javascript
  arrayObject.join( separator );
  ```

##### 参数说明:

  - separator - 可选。指定要使用的分隔符。如果省略该参数，则使用逗号作为分隔符。

##### 返回值:

  返回一个字符串。该字符串是通过把 arrayObject 的每个元素转换为字符串，然后把这些字符串连接起来，在两个元素之间插入 separator 字符串而生成的。

###### 示例:

  ```javascript
  var Arr = [1, 2, 3, 4, 5, 6];
	  
  console.log( Arr.join() );
  console.log( Arr.join('-') );
  ```

###### 结果:

  ```javascript
  >>>
  1,2,3,4,5,6
  1-2-3-4-5-6
  ```
