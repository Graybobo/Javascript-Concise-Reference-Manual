#### floor() 方法

  floor() -- 对一个数进行下舍入

##### 语法:

  ```javascript
  Math.floor( x );
  ```

##### 参数说明:

  x -- 任意数值或表达式
  
##### 返回值:

  小于等于 x，且与 x 最接近的整数。

##### 说明:

  floor() 方法执行的是向下取整计算，它返回的是小于或等于函数参数，并且与之最接近的整数。
   
###### 示例:

  ```javascript
  console.log( Math.floor( 0.20 ) );
  console.log( Math.floor( 0.70 ) );
  console.log( Math.floor( 0 ) );
  console.log( Math.floor( 5 ) );
  console.log( Math.floor( 5.7 ) );
  console.log( Math.floor( -5.7 ) );
  ```

###### 结果:

  ```javascript
  >>>
  0
  0
  0
  5
  5
  -6
  ```
