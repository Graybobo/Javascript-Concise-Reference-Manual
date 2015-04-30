#### toString 方法

  把数组转换为字符串。

##### 语法:

  ```javascript
  arrayObject.toString();
  ```

##### 返回值:

  arrayObject 的字符串表示。返回值与没有参数的 join() 方法返回的字符串相同。
  
##### 说明:

  当数组用于字符串环境时，JavaScript 会调用这一方法将数组自动转换成字符串。但是在某些情况下，需要显式地调用该方法。
  
###### 示例:

  ```javascript
  var Arr = [11, 2, 73, 41, 53, 6, 38, 9, 40],
      s = Arr.toString(); 

  console.log( s );
  console.log( typeof s );
  ```

###### 结果:

  ```javascript
  >>>
  11,2,73,41,53,6,38,9,40
  string
  ```
