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

### 正则表达式( RegExp )

  - RegExp 对象属性

    - [global](/RegExp/global.md) - RegExp 对象是否具有标志 g
    - [ignoreCase](/RegExp/ignoreCase.md) - RegExp 对象是否具有标志 i
    - [lastIndex](/RegExp/lastIndex.md) - 一个整数 标示开始下一次匹配的字符位置
    - [multiline](/RegExp/multiline.md) - RegExp 对象是否具有标志 m
    - [source](/RegExp/source.md) - 正则表达式的源文本
	
  - RegExp 对象方法

    - [compile()](/RegExp/compile.md) - 编译正则表达式
    - [exec()](/RegExp/exec.md) - 检索字符串中指定的值 返回找到的值 并确定其位置
    - [test()](/RegExp/test.md) - 检索字符串中指定的值 返回 true 或 false

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
    - [acos(x)](/Math/acos.md) - 返回数的反余弦值
    - [asin(x)](/Math/asin.md) - 返回数的反正弦值
    - [atan(x)](/Math/atan.md) - 以介于 -PI/2 与 PI/2 弧度之间的数值来返回 x 的反正切值
    - [atan2(y,x)](/Math/atan2.md) - 返回从 x 轴到点( x, y )的角度( 介于 -PI/2 与 PI/2 弧度之间 )
    - [ceil(x)](/Math/ceil.md) - 对数进行上舍入
    - [cos(x)](/Math/cos.md) - 返回数的余弦
    - [exp(x)](/Math/exp.md) - 返回 e 的指数
    - [floor(x)](/Math/floor.md) - 对数进行下舍入
    - [log(x)](/Math/log.md) - 返回数的自然对数( 底为e )
    - [max(x,y,...)](/Math/max.md) - 返回数个数字中较大的值
    - [min(x,y,...)](/Math/min.md) - 返回数个数字中较小的值
    - [pow(x,y)](/Math/pow.md) - 返回 x 的 y 次幂
    - [random()](/Math/random.md) - 返回 0 ~ 1 之间的随机数
    - [round(x)](/Math/round.md) - 把数四舍五入为最接近的整数
    - [sin(x)](/Math/sin.md) - 返回数的正弦值
    - [sqrt(x)](/Math/sqrt.md) - 返回数的平方根
    - [tan(x)](/Math/tan.md) - 返回数的正切值
    - [toSource()](/Math/toSource.md) - 返回该对象的源代码
    - [valueOf()](/Math/valueOf.md) - 返回 Math 对象的原始值

### Date

  - Date 对象属性

    - [constructor](/Date/constructor.md) - 返回对创建此对象的 Date 函数的引用
    - [prototype](/Date/prototype.md) - 使您有能力向对象添加属性和方法

  - Date 对象方法

    - [Date()](/Date/Date.md) - 返回当天的日期和时间
    - [getDate()](/Date/getDate.md) - 从 Date 对象返回一个月中的某一天( 1 ~ 31 )
    - [getDay()](/Date/getDay.md) - 从 Date 对象返回一周中的某一天( 0 ~ 6 )
    - [getMonth()](/Date/getMonth.md) - 从 Date 对象返回月份( 0 ~ 11 )
    - [getFullYear()](/Date/getFullYear.md) - 从 Date 对象以四位数字返回年份
    - [getYear()](/Date/getYear.md) - 从 Date 对象返回表示年份的两位或四位的数字
    - [getHours()](/Date/getHours.md) - 返回 Date 对象的小时( 0 ~ 23 )
    - [getMinutes()](/Date/getMinutes.md) - 返回 Date 对象的分钟( 0 ~ 59 )
    - [getSeconds()](/Date/getSeconds.md) - 返回 Date 对象的秒数( 0 ~ 59 )
    - [getMilliseconds()](/Date/getMilliseconds.md) - 返回 Date 对象的毫秒( 0 ~ 999 )
    - [getTime()](/Date/getTime.md) - 返回 1970 年 1 月 1 日至今的毫秒数
    - [getTimezoneOffset()](/Date/getTimezoneOffset.md) - 返回本地时间与格林威治标准时间( GMT )的分钟差
    - [getUTCDate()](/Date/getUTCDate.md) - 根据世界时从 Date 对象返回月中的一天( 1 ~ 31 )
    - [getUTCDay()](/Date/getUTCDay.md) - 根据世界时从 Date 对象返回周中的一天( 0 ~ 6 )
    - [getUTCMonth()](/Date/getUTCMonth.md) - 根据世界时从 Date 对象返回月份( 0 ~ 11 )
    - [getUTCFullYear()](/Date/getUTCFullYear.md) - 根据世界时从 Date 对象返回四位数的年份
    - [getUTCHours()](/Date/getUTCHours.md) - 根据世界时返回 Date 对象的小时( 0 ~ 23 )
    - [getUTCMinutes()](/Date/getUTCMinutes.md) - 根据世界时返回 Date 对象的分钟( 0 ~ 59 )
    - [getUTCSeconds()](/Date/getUTCSeconds.md) - 根据世界时返回 Date 对象的秒钟( 0 ~ 59 )
    - [getUTCMilliseconds()](/Date/getUTCMilliseconds.md) - 根据世界时返回 Date 对象的毫秒( 0 ~ 999 )
    - [parse()](/Date/parse.md) - 返回 1970 年 1 月 1 日午夜到指定日期( 字符串 )的毫秒数
    - [setDate()](/Date/setDate.md) - 设置 Date 对象中月份的某一天( 1 ~ 31 )
    - [setMonth()](/Date/setMonth.md) - 设置 Date 对象中月份( 0 ~ 11 )
    - [setFullYear()](/Date/setFullYear.md) - 设置 Date 对象中的年份( 四位数字 )
    - [setYear()](/Date/setYear.md) - 设置 Date 对象中的年份( 推荐使用 setFullYear() 方法代替 )
    - [setHours()](/Date/setHours.md) - 设置 Date 对象中的小时( 0 ~ 23 )
    - [setMinutes()](/Date/setMinutes.md) - 设置 Date 对象中的分钟( 0 ~ 59 )
    - [setSeconds()](/Date/setSeconds.md) - 设置 Date 对象中的秒钟( 0 ~ 59 )
    - [setMilliseconds()](/Date/setMilliseconds.md) - 设置 Date 对象中的毫秒( 0 ~ 999 )
    - [setTime()](/Date/setTime.md) - 以毫秒设置 Date 对象
    - [setUTCDate()](/Date/setUTCDate.md) - 根据世界时设置 Date 对象中月份的一天( 1 ~ 31 )
    - [setUTCMonth()](/Date/setUTCMonth.md) - 根据世界时设置 Date 对象中的月份( 0 ~ 11 )
    - [setUTCFullYear()](/Date/setUTCFullYear.md) - 根据世界时设置 Date 对象中的年份( 四位数字 )
    - [setUTCHours()](/Date/setUTCHours.md) - 根据世界时设置 Date 对象中的小时( 0 ~ 23 )
    - [setUTCMinutes()](/Date/setUTCMinutes.md) - 根据世界时设置 Date 对象中的分钟( 0 ~ 59 )
    - [setUTCSeconds()](/Date/setUTCSeconds.md) - 根据世界时设置 Date 对象中的秒钟( 0 ~ 59 )
    - [setUTCMilliseconds()](/Date/setUTCMilliseconds.md) - 根据世界时设置 Date 对象中的毫秒( 0 ~ 999 )
    - [toSource()](/Date/toSource.md) - 返回该对象的源代码
    - [toString()](/Date/toString.md) - 把 Date 对象转换为字符串
    - [toTimeString()](/Date/toTimeString.md) - 把 Date 对象的时间部分转换为字符串
    - [toDateString()](/Date/toDateString.md) - 把 Date 对象的日期部分转换为字符串
    - [toGMTString()](/Date/toGMTString.md) - 根据格林威治时间( GMT )把 Date 对象转换为字符串
    - [toUTCString()](/Date/toUTCString.md) - 根据世界时 把 Date 对象转换为字符串
    - [toLocaleString()](/Date/toLocaleString.md) - 根据本地时间格式 把 Date 对象转换为字符串
    - [toLocaleTimeString()](/Date/toLocaleTimeString.md) - 根据本地时间格式 把 Date 对象的时间部分转换为字符串
    - [toLocaleDateString()](/Date/toLocaleDateString.md) - 根据本地时间格式 把 Date 对象的日期部分转换为字符串
    - [UTC()](/Date/UTC.md) - 根据世界时返回 1970 年 1 月 1 日 到指定日期的毫秒数
    - [valueOf()](/Date/valueOf.md) - 返回 Date 对象的原始值

### Boolean

  - Boolean 对象属性
    
    - [constructor](/Boolean/constructor.md) - 返回对创建此对象的 Boolean 函数的引用
    - [prototype](/Boolean/prototype.md) - 使您有能力向对象添加属性和方法

  - Boolean 对象方法
  
    - [toSource()](/Boolean/toSource.md) - 返回该对象的源代码
    - [toString()](/Boolean/toString.md) - 把逻辑值转换为字符串 并返回结果
    - [valueOf()](/Boolean/valueOf.md) - 返回 Boolean 对象的原始值

### Number

  - Number 对象属性

    - [constructor](/Number/constructor.md) - 返回对创建此对象的 Number 函数的引用
    - [MAX_VALUE](/Number/MAX_VALUE.md) - 可表示的最大的数
    - [MIN_VALUE](/Number/MIN_VALUE.md) - 可表示的最小的数
    - [NaN](/Number/NaN.md) - 非数字值
    - [NEGATIVE_INFINITY](/Number/NEGATIVE_INFINITY.md) - 负无穷大 溢出时返回该值
    - [POSITIVE_INFINITY](/Number/POSITIVE_INFINITY.md) - 正无穷大 溢出时返回该值
    - [prototype](/Number/prototype.md) - 使您有能力向对象添加属性和方法

  - Number 对象方法

    - [toString()](/Number/toString.md) - 把数字转换为字符串 使用指定的基数
    - [toLocaleString()](/Number/toLocaleString.md) - 把数字转换为字符串 使用本地数字格式顺序
    - [toFixed()](/Number/toFixed.md) - 把数字转换为字符串 结果的小数点后有指定位数的数字
    - [toExponential()](/Number/toExponential.md) - 把对象的值转换为指数计数法
    - [toPrecision()](/Number/toPrecision.md) - 把数字格式化为指定的长度
    - [valueOf()](/Number/valueOf.md) - 返回一个 Number 对象的基本数字值

### String

  - String 对象属性

    - [constructor](/String/constructor.md) - 返回对创建此对象的 String 函数的引用
    - [length](/String/length.md) - 返回字符串的长度
    - [prototype](/String/prototype.md) - 使您有能力向对象添加属性和方法

  - String 对象方法

    - [anchor()](/String/anchor.md) - 创建 HTML 锚
    - [big()](/String/big.md) - 用大号字体显示字符串
    - [blink()](/String/blink.md) - 显示闪动字符串
    - [bold()](/String/bold.md) - 用粗体显示字符串
    - [charAt()](/String/charAt.md) - 返回在指定位置的字符
    - [charCodeAt()](/String/charCodeAt.md) - 返回在指定的位置的字符的 Unicode 编码
    - [concat()](/String/concat.md) - 连接字符串
    - [fixed()](/String/fixed.md) - 以打字机文本显示字符串
    - [fontcolor()](/String/fontcolor.md) - 使用指定的颜色来显示字符串
