#### asin() 方法

  asin() -- 返回数的反正弦值

##### 语法:

  ```javascript
  Math.asin( x );
  ```

##### 参数说明:

  x -- [ -1.0 ~ 1.0 ] 之间的一个数值
  
##### 返回值:

  x 的反正弦值。返回的值是 -PI/2 到 PI/2 之间的弧度值。
  
##### 说明:

  - 如果参数 x 超过了 -1.0 ~ 1.0 的范围，那么浏览器将返回 NaN。
  - 如果参数 x 取值 1，那么将返回 PI/2。
   
###### 示例:

  ```javascript
  console.log( Math.asin( 0.31 ) );
  console.log( Math.asin( 0 ) );
  console.log( Math.asin( -1 ) );
  console.log( Math.asin( 1 ) );
  console.log( Math.asin( 5 ) );
  ```

###### 结果:

  ```javascript
  >>>
  0.31519303244072444
  0
  -1.5707963267948966
  1.5707963267948966
  NaN
  ```
