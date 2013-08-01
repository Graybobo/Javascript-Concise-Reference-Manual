#### atan() 方法

  atan() -- 返回数的反正切值

##### 语法:

  ```javascript
  Math.atan( x );
  ```

##### 参数说明:

  x -- 一个数值
  
##### 返回值:

  x 的反正切值。返回的值是 -PI/2 到 PI/2 之间的弧度值。
   
###### 示例:

  ```javascript
  console.log( Math.atan( 0.30 ) );
  console.log( Math.atan( -0.30 ) );
  console.log( Math.atan( 3 ) );
  console.log( Math.atan( -3 ) );
  console.log( Math.atan( 10 ) );
  console.log( Math.atan( -10 ) );
  ```

###### 结果:

  ```javascript
  >>>
  0.2914567944778671
  -0.2914567944778671
  1.2490457723982544
  -1.2490457723982544
  1.4711276743037347
  -1.4711276743037347
  ```
