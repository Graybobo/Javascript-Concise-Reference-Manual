#### toLocaleString 方法

  把一个 Number 对象转换为本地格式的字符串。

##### 语法:

  ```javascript
  NumberObject.toLocaleString();
  ```

##### 返回值:

  数字的字符串表示，由实现决定，根据本地规范进行格式化，可能影响到小数点或千分位分隔符采用的标点符号。

##### 异常抛出:

  当调用该方法的对象不是 Number 时抛出 TypeError 异常。

###### 示例:

  ```javascript
  var Num = new Number( 123456 ),
      n = Num.toLocaleString();
	  
  console.log( n );
  console.log( typeof n );
  ```

###### 结果:

  ```javascript
  >>>
  123,456
  string
  ```
