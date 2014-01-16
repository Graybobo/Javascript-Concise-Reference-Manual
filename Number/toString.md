#### toString 方法

  把一个 Number 对象转换为一个字符串，并返回结果。

##### 语法:

  ```javascript
  NumberObject.toString( radix );
  ```
##### 参数说明:

  radix - 可选。规定表示数字的基数，使 2 ~ 36 之间的整数。若省略该参数，则使用基数 10。但是要注意，如果该参数是 10 以外的其他值，则 ECMAScript 标准允许实现返回任意值。

##### 返回值:

  数字的字符串表示。例如，当 radix 为 2 时，NumberObject 会被转换为二进制值表示的字符串。

##### 异常抛出:

  当调用该方法的对象不是 Number 时抛出 TypeError 异常。

###### 示例:

  ```javascript
  var Num = new Number( 123456 ),
      n = Num.toString();
	  
  console.log( n );
  console.log( typeof n );
  ```

###### 结果:

  ```javascript
  >>>
  123456
  string
  ```
