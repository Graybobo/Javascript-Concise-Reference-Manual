#### sin() 方法

  sin() -- 返回数的正弦值

##### 语法:

  ```javascript
  Math.sin( x );
  ```

##### 参数说明:

  x -- Number 类型的弧度( 将角度乘以 0.017453293 （2PI/360）即可转换为弧度 )。
  
##### 返回值:

  x 的正弦值。返回值在 -1.0 到 1.0 之间。
   
###### 示例:

  ```javascript
  console.log( Math.sin( 2 ) );
  console.log( Math.sin( -2 ) );
  console.log( Math.sin( 0 ) );
  console.log( Math.sin( Math.PI ) );
  console.log( Math.sin( Math.PI/2 ) );
  ```

###### 结果:

  ```javascript
  >>>
  0.9092974268256817
  -0.9092974268256817
  0
  1.2246467991473532e-16
  1
  ```
