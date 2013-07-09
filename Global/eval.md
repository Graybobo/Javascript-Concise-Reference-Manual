#### Javascript eval() 函数

  eval() -- 计算 JavaScript 字符串，并把它作为脚本代码来执行。

##### 语法:

  ```javascript
  eval( CODEstring );
  ```

##### 参数说明:

  CODEstring -- 代码字符串，其中含有要计算的 JavaScript 表达式或要执行的语句。

##### 返回值:

  - 如果没有参数，返回undefined
  - 如果有返回值将返回此值，否则返回undefined
  - 如果为表达式，返回表达式的值
  - 如果为语句返回语句的值
  - 如果为多条语句或表达式返回最后一条语句的值

##### 说明：

  - 该方法只接受原始字符串作为参数，如果 string 参数不是原始字符串，那么该方法将不作任何改变地返回。因此请不要为 eval() 函数传递 String 对象来作为参数。
  - 如果试图覆盖 eval 属性或把 eval() 方法赋予另一个属性，并通过该属性调用它，则 ECMAScript 实现允许抛出一个 EvalError 异常。
  - 虽然 eval() 的功能非常强大，但在实际使用中用到它的情况并不多。常用来解析 JSON 对象。

##### 异常说明：

  - SyntaxError -- codes 中有非法的 Javascript 表达式或语句
  - EvalError -- 非法调用 eval 函数
  - Error -- 当 eval 解析的 Javascript 表达式或语句出现异常时，eval 也会抛出这个异常。

  如果参数中没有合法的表达式和语句，则抛出 SyntaxError 异常。

  如果非法调用 eval()，则抛出 EvalError 异常。

  如果传递给 eval() 的 Javascript 代码生成了一个异常，eval() 将把该异常传递给调用者。
