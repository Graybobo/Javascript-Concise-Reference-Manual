#### parse() 方法

  解析一个日期时间字符串，并返回 1970/1/1 午夜距离该日期时间的毫秒数。

##### 语法:

  ```javascript
  Date.parse( dateString )
  ```

##### 参数说明:

  dateString -- 表示日期和时间的字符串

##### 返回值:

  指定的日期和时间据 1970/1/1 午夜( GMT 时间 )之间的毫秒数。

##### 说明:

  - Date.parse() 是 Date 对象的静态方法。
  - 一般采用 Date.parse() 的形式来调用，而不是通过 dateobject.parse() 调用该方法。

###### 示例:

  ```javascript
  var v = Date.parse( '2013-10-10' );
  console.log( v );
  ```

###### 结果:

  ```javascript
  >>>
  1381363200000
  ```
