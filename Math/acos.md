#### acos() 方法

  acos() -- 返回数的反余弦值

##### 语法:

  ```javascript
  Math.acos( x );
  ```

##### 参数说明:

  x -- [ -1.0 ~ 1.0 ] 之间的数
  
##### 返回值:

  x 的反余弦值。返回的值是 0 到 PI 之间的弧度值。
  
##### 说明:

  - 如果参数 x 超过了 -1.0 ~ 1.0 的范围，那么浏览器将返回 NaN。
  - 如果参数 x 取值 -1，那么将返回 PI。
   
###### 示例:

  ```javascript
  console.log( Math.acos( 0.31 ) );
  console.log( Math.acos( 0 ) );
  console.log( Math.acos( -1 ) );
  console.log( Math.acos( 1 ) );
  console.log( Math.acos( 5 ) );
  ```

###### 结果:

  ```javascript
  >>>
  1.2556032943541722
  1.5707963267948966
  3.141592653589793
  0
  NaN
  ```
