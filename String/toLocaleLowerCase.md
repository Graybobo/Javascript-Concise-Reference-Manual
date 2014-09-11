#### toLocaleLowerCase 方法

  把字符串转换为小写。

##### 语法:

  ```javascript
  stringObject.toLocaleLowerCase();
  ```

##### 返回值:

  一个新的字符串，在其中 stringObject 的所有大写字符全部被转换为了小写字符。

##### 说明:

  与 toLowerCase() 不同的是，toLocaleLowerCase() 方法按照本地方式把字符串转换为小写。只有几种语言（如土耳其语）具有地方特有的大小写映射，所有该方法的返回值通常与 toLowerCase() 一样。

###### 示例:

  ```javascript
  var Str = "Hello KILLHAPPY";
	  
  console.log( Str.toLocaleLowerCase() );
  ```

###### 结果:

  ```javascript
  >>>
  hello killhappy
  ```
