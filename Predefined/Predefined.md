## 预定义的全局变量和函数:

  Javascript 预定义了很多全局变量和函数，应当避免把它们用做变量名和函数名。如果用它们创建变量或函数，就会得到一个错误( 如果为只读 )或重定义了已经存在的变量或函数。不应该这样做，除非绝对明确自己在做什么。

  - arguments
  - Array
  - Boolean
  - Date
  - decodeURI
  - decodeURIComponent
  - encodeURI
  - encodeURIComponent
  - Error
  - escape
  - eval
  - EvalError
  - Function
  - Infinity
  - isFinite
  - isNaN
  - JSON
  - Math
  - NaN
  - Number
  - Object
  - parseFloat
  - parseInt
  - RangeError
  - ReferenceError
  - RegExp
  - String
  - SyntaxError
  - TypeError
  - undefined
  - unescape
  - URIError
  
  Javascript 的具体实现可能定义独有的全局变量和函数，每一种特定的 Javascript 运行环境( 客户端、服务器端等 )都有自己的一个全局属性列表。
