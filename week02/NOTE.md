# 第二周学习总结

## 编程语言通识
### 语言按语法分类
- 非形式语言
  * 中文
  * 英文
- 形式语言(乔姆斯基谱系)
  * 0型: 无限制文法
  * 1型: 上下文相关文法
  * 2型: 上下文无关文法
  * 3型: 正则文法

### 形式语言产生式
- BNF
  * 语法结构
    + 基础结构称终结符
    + 符合结构称非终结符
  * 符号
    + (): 括号
    + *: 表示重复多次
    + |: 表示或
    + +: 表示至少一次
- EBNF
- ABNF

### 图灵完备性
- 命令式(图灵机)
  * goto
  * if和while
- 声明式(lamdba)
  * 递归

### 类型系统
- 按动静划分
  * 动态类型系统
    + 在用户的设备/在线服务器上运行
    + 产品实际运行时
    + Runtime
  * 静态类型系统
    + 在程序员的设备上
    + 产品开发时
    + Compiletime
- 按是否隐式转换划分
  * 强类型
  * 弱类型
- 按复合类型划分
  * 结构体
  * 函数签名
- 继承
  * 逆变
  * 协变

### 一般命令式编程语言
- Atom
  * Identifier
  * Literal
- Expression
  * Atom
  * Operator
  * Punctuator
- Statement
  * Expression
  * Keyworkd
  * Punctuator
- Structure
  * Function
  * Class
  * Process
  * Namespace
- Program
  * Module
  * Package
  * Library

## Javascript
### Unicode
- [学习文档一](https://www.fileformat.info/info/unicode/)
- [学习文档二](https://home.unicode.org)

### InputElement
- WhiteSpace
  * TAB
  * VT: 纵向制表符
  * FF: Form Feed
  * SP
  * NBSP: 处理排版时，如果是普通的SP，会在一行放不下时，将它左右断开;NBSP它的左右不会断开
  * ZWNBSP
  * USP
- LineTerminator
  * LF: \n
  * CR: \r
  * LS
  * PS
- Comment
  * //
  * /**/
- Token
  * Punctuator符号
  * IdentifierName
    + Identifier标识符(变量/属性)
    + Keywords关键字
    + Future reserved Keywords(保留字) : enum
  * Literal直接量
    + Number
    + String
    + Boolean
    + Null
    + Undefined