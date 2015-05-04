#### toLocaleString 方法

  把数组转换为字符串。

##### 语法:

  ```javascript
  arrayObject.toLocaleString();
  ```

##### 返回值:

  arrayObject 的本地字符串表示。
  
##### 说明:

  首先调用每个数组元素的 toLocaleString() 方法，然后使用地区特定的分隔符把生成的字符串连接起来，形成一个字符串。
  
###### 示例:

  ```javascript
  var Arr = [10, 2, 73, 41, 53, 6, 38, 9, 40],
      s = Arr.toLocaleString(); 

  console.log( s );
  console.log( typeof s );
  ```

###### 结果:

  ```javascript
  >>>
  10,2,73,41,53,6,38,9,40
  string
  ```
