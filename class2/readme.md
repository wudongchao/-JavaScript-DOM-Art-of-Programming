### JavaScript语法
###### JavaScript语法包括语句、变量和数组、操作符、条件语句和循环语句、函数和对象。
###### JavaScript语法只要遵循规则，所表达的意思就可以被正确地解读。

##### JavaScript语句
###### JavaScript编写的脚本由一系列指令构成，这些指令叫做语句（statement）。只有按照正确的语法编写出来的语句才能得到正确的解释。

##### JavaScript注释
###### JavaScript解释器不需要去解释并执行会忽略的信息。仅供自己参考或者提醒自己的信息。如：// 单行注释和 "/*多行*/" 多行注释及 “<!--大段-->” 大段注释

##### JavaScript变量
###### 变量即会发生变化的东西（variable）
###### JavaScript提前声明变量是一个良好的编程习惯
###### 一行可以声明多个变量; var mood = "happy", age = 33;
###### 变量和其他语法元素的名字都是区分字母大小写的
###### 变量名中不允许包含空格或者标点符号（美元符号“$”除外）
###### 变量名允许包含字母、数字、美元符号和下划线（但第一个字符不允许是数字）
###### 变量名可以使用驼峰格式（camel case）,如：myMood
###### 使用关键字“var”来声明变量

#### JavaScript数据类型
###### JavaScript是弱类型（weakly typed）语言。这意味着程序员在任何阶段都可以改变变量的数据类型

##### JavaScript字符串
###### 字符串由零个或者多个字符构成，字符包括（但不限于）字母、数字、标点符号和空格。
###### 字符串必须在双引号或者单引号里。如：var mood = 'happy'; var mood = "happy"
###### var mood = "don't ask" ,如果想在上面这条语句中使用单引号，就必须保证字母“n”和“t”之间的单引号能够被当成这个字符串的一部分，这种情况就需要转义。JavaScript用反斜线对字符进行转义：var mood = 'don\’t ask';
###### 如果是双引号，就必须用反斜线对字符串中的双引号就行转义。var height = "about 5'10\" tall";var height ="about 5'10\"tall"

##### JavaScript 数值
###### JavaScript允许使用带小数点的树枝，并且允许任意位小数，这样的数称为浮点数（floating- point number）; 
###### var age = 33; var temperature = -20; var temerature = -20.333;

##### JavaScript布尔值
###### JavaScript数据类型只有两个可选 true和false。 var sleeoing = true;

#### JavaScript数组
###### JavaScript数组指用一个变量表示一个值的集合，集合中的每个值都是这个数组的一个元素。
###### 数组见index.html 2.1
###### 关联数组见 index.html 2.1.1

#### JavaScript对象
###### 与数组类似，对象也是使用一个名字表示一组值，对象的每个值都是对象的一个属性。
###### 对象见index.html 2.2

#### JavaScript操作符
###### 算术操作符，加减乘除。 “+”，“-”，"✳"，“/”，可用括号分隔。1 + (4 * 5);
###### 算术操作符见index.html 2.3

#### JavaScript条件语句
###### JavaScript使用条件语句（conditional statement）来做判断
###### JavaScript使用条件语句来设置一个条件，只有满足了这一条件才能让更语句块中的语句得到执行。
###### 条件语句见index.html 2.4

#### JavaScript逻辑操作符
###### 大于 小于 等于 大于等于 小于等于 ">" "<" "=" ">=" "<="
###### 或使用 “&&” 和 “||” 来连接，两次比较操作称为逻辑比较（operand）
###### "逻辑非"操作符，它由一个感叹号"!"单独构成。
###### 逻辑操作符见index.html 2.5
###### 字符串、数值和布尔值都是标量