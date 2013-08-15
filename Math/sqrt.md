#### sqrt() 方法

  sqrt() -- 返回数的平方根

##### 语法:

  ```javascript
  Math.sqrt( x );
  ```

##### 参数说明:

  x -- 大于等于 0 的数
  
##### 返回值:

  参数 x 的平方根。如果 x 小于 0，则返回 NaN。
   
###### 示例:

  ```javascript
  console.log( Math.sqrt( 1 ) );
  console.log( Math.sqrt( -1 ) );
  console.log( Math.sqrt( 0 ) );
  console.log( Math.sqrt( 7 ) );
  console.log( Math.sqrt( 0.49 ) );
  ```

###### 结果:

  ```javascript
  >>>
  1
  NaN
  0
  2.6457513110645907
  0.7
  ```
