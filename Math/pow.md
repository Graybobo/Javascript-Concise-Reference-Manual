#### pow() 方法

  pow() -- 返回 x 的 y 次幂的值

##### 语法:

  ```javascript
  Math.pow(x,y);
  ```

##### 参数说明:

 - x -- 底数( 必须是数字 )
 - y -- 幂数( 必须是数字 )
  
##### 返回值:

  x 的 y 次幂值

##### 说明:

  如果结果是虚数或负数，则该方法将返回 NaN。如果由于指数过大而引起浮点溢出，则该方法将返回 Infinity。
   
###### 示例:

  ```javascript
  console.log( Math.pow( 0, 0 ) );
  console.log( Math.pow( 0, 1 ) );
  console.log( Math.pow( 1, 1 ) );
  console.log( Math.pow( 1, 5 ) );
  console.log( Math.pow( 2, 3 ) );
  console.log( Math.pow( -2, 3 ) );
  console.log( Math.pow( 2, 4 ) );
  console.log( Math.pow( -2, 4 ) );
  ```

###### 结果:

  ```javascript
  >>>
  1
  0
  1
  1
  8
  -8
  16
  16
  ```
