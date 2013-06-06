Javascript-Concise-Reference-Manual
===================================

<https://github.com/Graybobo/Javascript-Concise-Reference-Manual>

( 参考 ECMAScript3 标准和 ECMAScript5 标准部分内容，对 ECMAScript3 和 ECMAScript5 不符/存在差异的内容和存在争议之处请视实际情况处之或以相关标准规范为准！ )

**Javascript 关键词&&保留字:**

  - [Javascript 关键词](/Keywords/Keywords.md)
  - [Javascript 保留字](/Reserved/Reserved-words.md)
  - [预定义的全局变量和函数](/Predefined/Predefined.md)
  
**严格模式( Strict mode ):**

  ```javascript
  "use strict";
  ```

**数据类型( Types ):**

  - String       ( Primitive type )
  - Number       ( Primitive type )
  - Boolean      ( Primitive type )
  - null         ( Primitive type )
  - undefined    ( Primitive type )
  - Object       ( Object type )

**操作符( 运算符 ):**

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
