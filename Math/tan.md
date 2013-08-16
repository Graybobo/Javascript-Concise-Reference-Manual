#### tan() 方法

  tan() -- 返回数的正切值

##### 语法:

  ```javascript
  Math.tan( x );
  ```

##### 参数说明:

  x -- Number 类型的弧度值( 将角度乘以 0.017453293 ( 2PI/360 )即可转换为弧度 )
  
##### 返回值:

  参数 x 的正切值。
   
###### 示例:

  ```javascript
  console.log( Math.tan( 1 ) );
  console.log( Math.tan( -1 ) );
  console.log( Math.tan( 0 ) );
  console.log( Math.tan( 0.5 ) );
  console.log( Math.tan( -0.5 ) );
  ```

###### 结果:

  ```javascript
  >>>
  1.5574077246549023
  -1.5574077246549023
  0
  0.5463024898437905
  -0.5463024898437905
  ```
