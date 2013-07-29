#### toSource 方法

  toSource() 方法返回表示对象源代码的字符串。

##### 语法:

  ```javascript
  Object.toSource();
  ```

##### 注:

  该方法在 Internet Explorer 中无效。
  
###### 示例:

  ```javascript
  function Engineer( name, language ){
      this.name = name;
	  this.lang = language;
  }
  var Graybobo = new Engineer( 'KILLHAPPY', 'Nodejs' );
  
  console.log( Graybobo.toSource() );
  console.log( typeof ( Graybobo.toSource() ) );
  ```

###### 结果:

  ```javascript
  >>>
  ({name:"KILLHAPPY", lang:"Nodejs"})
  string
  ```
