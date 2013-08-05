#### ceil() 方法

  ceil() -- 对数进行上舍入

##### 语法:

  ```javascript
  Math.ceil( x );
  ```

##### 参数说明:

  x -- 待处理的数值
  
##### 返回值:

  大于等于 x ，并且与它最接近的整数。

##### 说明:

  ceil() 方法执行的是向上取整计算，它返回的是大于或等于函数参数，并且与之最接近的整数。
   
###### 示例:

  ```javascript
  console.log( Math.ceil( 0.80 ) );
  console.log( Math.ceil( 0.30 ) );
  console.log( Math.ceil( 5 ) );
  console.log( Math.ceil( 5.3 ) );
  console.log( Math.ceil( -5.3 ) );
  console.log( Math.ceil( -5.8 ) );
  ```

###### 结果:

  ```javascript
  >>>
  1
  1
  5
  6
  -5
  -5
  ```
