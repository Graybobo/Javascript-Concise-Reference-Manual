#### min() 方法

  min() -- 返回数个数字中较小的值

##### 语法:

  ```javascript
  Math.min( x, y, ... );
  ```

##### 参数说明:

  0 或多个值( Number类型值 )。在 ECMASCript v3 之前，该方法只有两个参数。
  
##### 返回值:

  - 返回数个数值中较小的值
  - 如果没有参数，则返回 Infinity
  - 如果有某个参数为 NaN，或是不能转换成数字的非数字值，则返回 NaN。
   
###### 示例:

  ```javascript
  console.log( Math.min( 1, 3 ) );
  console.log( Math.min( 5, 1, 0, 10, 7 ) );
  console.log( Math.min() );
  console.log( Math.min( 0 ) );
  console.log( Math.min( 'x', 1 ) );
  ```

###### 结果:

  ```javascript
  >>>
  1
  0
  Infinity
  0
  NaN
  ```
