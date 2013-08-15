#### round() 方法

  round() -- 把一个数字舍入为最接近的整数

##### 语法:

  ```javascript
  Math.round(x);
  ```

##### 参数说明:

  x -- 待处理的数字
  
##### 返回值:

  与 x 最接近的整数
  
##### 说明:

  对于 0.5，该方法将进行上舍入。
  
  ( 例如，3.5 将舍入为 4，而 -3.5 将舍入为 -3。)
   
###### 示例:

  ```javascript
  console.log( Math.round(0.80) );
  console.log( Math.round(0.50) );
  console.log( Math.round(0.49) );
  console.log( Math.round(-4.40) );
  console.log( Math.round(-4.50) );
  console.log( Math.round(-4.60) );
  ```

###### 结果:

  ```javascript
  >>>
  1
  1
  0
  -4
  -4
  -5
  ```
