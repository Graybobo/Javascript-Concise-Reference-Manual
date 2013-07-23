#### Javascript getClass() 函数

  getClass() -- 返回一个 JavaObject 的 JavaClass。

##### 语法:

  ```javascript
  getClass( javaObject );
  ```

##### 参数说明:

  javaObject -- 一个 JavaObject 对象

##### 返回值:

  javaObject 的 JavaClass 对象

##### 说明:

  getClass() 函数可接受一个 JavaObject 对象作为其参数，并返回该对象的 JavaClass，即返回 JavaClass 对象。该 JavaClass 对象表示 Java 对象的 Java 类，而这个 Java 对象所表示的 Java 类是由 JavaObject 指定的。

##### 注:

  请不要把 JavaScript 的 getClass() 函数与所有 Java 对象的 getClass 方法混淆在一起。也不要把 JavaScript 的 JavaClass 对象与 Java java.lang.Class 类混淆了。

###### 用法:

  请看下面这行代码，它可创建一个 Java Rectangle 对象：

  ```javascript
  var obj = new java.awt.Rectangle();
  ```
  
  obj 是一个保存了 JavaObject 的 JavaScript 变量。我们可以调用 JavaScript 函数 getClass() 返回一个 JavaClass 对象，该 JavaClass 对象表示 java.awt.Rectangle 类：
  
  ```javascript
  var cls = getClass( obj );
  ```
  
  而调用 Java getClass() 的方式有所不同，且执行完全不同的功能：
  
  ```javascript
  cls = obj.getClass();
  ```
  
  在执行了上面这行代码后，cls 是表示 java.lang.class 对象的一个 Java Object。这个 java.lang.class 对象是一个 Java 对象，它是 java.awt.Rectangle 类的一个 Java 表示。
  
  最后，对于任何的 JavaObject obj，您do会看到下面的表示式始终为 true：
  
  ```javascript
  (getClass(obj.getClass()) == java.lang.Class)
  ```
