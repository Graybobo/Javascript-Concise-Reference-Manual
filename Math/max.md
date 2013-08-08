#### max() 方法

  max() -- 返回数个数字中较大的值

##### 语法:

  ```javascript
  Math.max( x, y, ... );
  ```

##### 参数说明:

  0 或多个值( Number类型值 )。在 ECMASCript v3 之前，该方法只有两个参数。
  
##### 返回值:

  - 返回数个数值中较大的值
  - 如果没有参数，则返回 -Infinity
  - 如果有某个参数为 NaN，或是不能转换成数字的非数字值，则返回 NaN。
   
###### 示例:

  ```javascript
  console.log( Math.max( 1, 3 ) );
  console.log( Math.max( 5, 1, 0, 10, 7 ) );
  console.log( Math.max() );
  console.log( Math.max( 0 ) );
  console.log( Math.max( 'x', 10 ) );
  ```

###### 结果:

  ```javascript
  >>>
  3
  10
  -Infinity
  0
  NaN
  ```
