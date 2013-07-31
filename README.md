Javascript-Concise-Reference-Manual
===================================

<https://github.com/Graybobo/Javascript-Concise-Reference-Manual>

( 参考 ECMAScript3 标准和 ECMAScript5 标准部分内容，对 ECMAScript3 和 ECMAScript5 不符/存在差异的内容和存在争议之处请视实际情况处之或以相关标准规范为准！ )

### Javascript 关键词&&保留字

  - [Javascript 关键词](/Keywords/Keywords.md)
  - [Javascript 保留字](/Reserved/Reserved-words.md)
  - [预定义的全局变量和函数](/Predefined/Predefined.md)
  
### 严格模式( Strict mode )

  ```javascript
  "use strict";
  ```

### 数据类型( Types )

  - String              ( Primitive type )
  - Number              ( Primitive type )
  - Boolean             ( Primitive type )
  - null                ( Primitive type )
  - undefined           ( Primitive type )
  - Object              ( Object type )

### 操作符( 运算符 )

  - 算术操作符
  
    - `+`               [ 加法 ] 将两个数相加
    - `++`              [ 自增 ] 将表示数值的变量加一( 可以返回新值或旧值 )
    - `-`               [ 求相反数、减法 ] 作为求相反数操作符时 返回参数的相反数 | 作为二进制操作符时 将两个数相减
    - `--`              [ 自减 ] 将表示数值的变量减一( 可以返回新值或旧值 )
    - `*`               [ 乘法 ] 将两个数相乘
    - `/`               [ 除法 ] 将两个数相除
    - `%`               [ 求余 ] 求两个数相除的余数

  - 字符串操作符
  
    - `+`               [ 字符串加法 ] 连接两个字符串
    - `+=`              连接两个字符串 并将结果赋给第一个字符串
	
  - 逻辑操作符
  
    - `&&`              [ 逻辑与 ] 如果两个操作数都是真的话则返回真 否则返回假
    - `||`              [ 逻辑或 ] 如果两个操作数都是假的话则返回假 否则返回真
    - `!`               [ 逻辑非 ] 如果其单一操作数为真则返回假 否则返回真

  - 位操作符
  
    - `&`               [ 按位与 ] 如果两个操作数对应位都是 1 的话则在该位返回 1
    - `^`               [ 按位异或 ] 如果两个操作数对应位只有一个 1 的话则在该位返回 1
    - `|`               [ 按位或 ] 如果两个操作数对应位都是 0 的话则在该位返回 0
    - `~`               [ 求反 ] 反转操作数的每一位
    - `<<`              [ 左移 ] 将第一操作数的二进制形式的每一位向左移位 所移位的数目由第二操作数指定 右面的空位补零
    - `>>`              [ 算术右移 ] 将第一操作数的二进制形式的每一位向右移位 所移位的数目由第二操作数指定 忽略被移出的位
    - `>>>`             [ 逻辑右移 ] 将第一操作数的二进制形式的每一位向右移位 所移位的数目由第二操作数指定 忽略被移出的位 左面的空位补零

  - 赋值操作符
  
    - `=`               将第二操作数的值赋给第一操作数
    - `+=`              将两个数相加 并将和赋给第一个数
    - `-=`              将两个数相减 并将差赋给第一个数
    - `*=`              将两个数相乘 并将积赋给第一个数
    - `/=`              将两个数相除 并将商赋给第一个数
    - `%=`              计算两个数相除的余数 并将余数赋给第一个数
    - `&=`              执行按位与 并将结果赋给第一个操作数
    - `^=`              执行按位异或 并将结果赋给第一个操作数
    - `|=`              执行按位或 并将结果赋给第一个操作数
    - `<<=`             执行左移 并将结果赋给第一个操作数
    - `>>=`             执行算术右移 并将结果赋给第一个操作数
    - `>>>=`            执行逻辑右移 并将结果赋给第一个操作数

  - 比较操作符
  
    - `==`              如果操作数相等的话则返回真
    - `!=`              如果操作数不相等的话则返回真
    - `>`               如果左操作数大于右操作数的话则返回真
    - `>=`              如果左操作数大于等于右操作数的话则返回真
    - `<`               如果左操作数小于右操作数的话则返回真
    - `<=`              如果左操作数小于等于右操作数的话则返回真
    - `===`             判断恒等
    - `!==`             判断恒等

  - 特殊操作符
  
    - `?:`              [ 条件运算符 ] 执行一个简单的"if...else"语句
    - `,`               计算两个表达式，返回第二个表达式的值
    - `delete`          [ 删除属性 ]允许你删除一个对象的属性或数组中指定的元素
    - `new`             允许你创建一个用户自定义对象类型或内建对象类型的实例
    - `this`            可用于引用当前对象的关键字
    - `void`            该操作符指定了要计算一个表达式但不返回值
    - `typeof`          [ 检测操作数类型 ] 返回一个字符串 表明未计算的操作数的类型
    - `instanceof`      [ 测试对象类 ] 检查一个对象是否是某种类 返回布尔类型
    - `in`              检查属性是否存在
    - `.`               [ 对象属性存取运算符 ] 对象名.属性名
    - `[]`              [ 数组元素存取运算符 ] 数组名[下标]
    - `()`              [ 函数调用运算符 ] 其作用是调用函数

### 全局属性

  - [Infinity](/Global/Infinity.md) - 表示无穷大的数值属性
  - [NaN](/Global/NaN.md) - 表示非数字值属性
  - [undefined](/Global/undefined.md) - 表示未定义的值
  - [java.*](/Global/java.md) - 表示 java.* 包层级的 JavaPackage
  - [Packages](/Global/Packages.md) - 根 JavaPackage 对象

### 全局函数

  - [encodeURI()](/Global/encodeURI.md) - 把字符串作为 URI 进行编码
  - [decodeURI()](/Global/decodeURI.md) - 对 encodeURI 函数编码过的 URI 进行解码
  - [encodeURIComponent()](/Global/encodeURIComponent.md) - 把字符串作为 URI 组件进行编码
  - [decodeURIComponent()](/Global/decodeURIComponent.md) - 对 encodeURIComponent 函数编码的 URI 进行解码
  - [eval()](/Global/eval.md) - 计算 JavaScript 字符串，并把它作为脚本代码来执行
  - [isFinite()](/Global/isFinite.md) - 检查其参数是否是无穷大
  - [isNaN()](/Global/isNaN.md) - 检查某个值是否是数字
  - [Number()](/Global/Number.md) - 把对象的值转换为数字
  - [String()](/Global/String.md) - 把对象的值转换为字符串
  - [escape()](/Global/escape.md) - 对字符串进行编码/转义
  - [unescape()](/Global/unescape.md) - 对 escape() 编码过的字符串进行解码
  - [parseInt()](/Global/parseInt.md) - 解析字符串并返回一个整数
  - [parseFloat()](/Global/parseFloat.md) - 解析字符串并返回一个浮点数
  - [getClass()](/Global/getClass.md) - 返回一个 JavaObject 的 JavaClass

### Boolean

  - Boolean 对象属性
    
    - [constructor](/Boolean/constructor.md) - 返回对创建此对象的 Boolean 函数的引用
    - [prototype](/Boolean/prototype.md) - 使您有能力向对象添加属性和方法

  - Boolean 对象方法
  
    - [toSource()](/Boolean/toSource.md) - 返回该对象的源代码
    - [toString()](/Boolean/toString.md) - 把逻辑值转换为字符串 并返回结果
    - [valueOf()](/Boolean/valueOf.md) - 返回 Boolean 对象的原始值

### Math

  - Math 对象属性
  
    - [E](/Math/E.md) - 返回算术常量 e  即自然对数的底数( 约等于2.718 )
    - [LN2](/Math/LN2.md) - 返回 2 的自然对数( 约等于0.693 )
    - [LN10](/Math/LN10.md) - 返回 10 的自然对数( 约等于2.302 )
    - [LOG2E](/Math/LOG2E.md) - 返回以 2 为底的 e 的对数( 约等于 1.443 )
    - [LOG10E](/Math/LOG10E.md) - 返回以 10 为底的 e 的对数( 约等于0.434 )
    - [PI](/Math/PI.md) - 返回圆周率( 约等于3.14159 )
    - [SQRT1_2](/Math/SQRT1_2.md) - 返回返回 2 的平方根的倒数( 约等于 0.707 )
    - [SQRT2](/Math/SQRT2.md) - 返回 2 的平方根( 约等于 1.414 )

  - Math 对象方法

    - [abs(x)](/Math/abs.md) - 返回数的绝对值
