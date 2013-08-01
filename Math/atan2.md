#### atan2() 方法

  atan2(y,x) -- 返回从 x 轴到点 (x,y) 之间的角度。

##### 语法:

  ```javascript
  Math.atan2(y,x);
  ```

##### 参数说明:

  - y -- 指定点的 X 坐标值
  - x -- 指定点的 Y 坐标值
  
##### 返回值:

  -PI 到 PI 之间的值，是从 X 轴正向逆时针旋转到点 (x,y) 时经过的角度。

##### 说明:

  请注意这个函数的参数顺序，Y 坐标在 X 坐标之前传递。
   
###### 示例:

  ```javascript
  console.log( Math.atan2( 0.30, 0.30 ) );
  console.log( Math.atan2( -0.30, -0.30 ) );
  console.log( Math.atan2( 3, 3 ) );
  console.log( Math.atan2( -3, -3 ) );
  console.log( Math.atan2( 10, 10 ) );
  console.log( Math.atan2( -10, 10 ) );
  ```

###### 结果:

  ```javascript
  >>>
  0.7853981633974483
  -2.356194490192345
  0.7853981633974483
  -2.356194490192345
  0.7853981633974483
  -0.7853981633974483
  ```
