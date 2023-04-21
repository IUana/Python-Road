# Python-Road

## Day1		Python简介
### Python的优缺点
#### 优点
1. 简单明了，学习曲线低。
2. 开放源代码，拥有强大的社区和生态圈。
3. 解释型语言，天生具有平台可移植性。
4. 代码规范程度高，可读性强。
#### 缺点
1. 执行效率稍低。
2. 代码无法加密。
3. 在开发时可以选择的框架太多。
### Python的应用领域
目前Python在Web应用后端开发、云基础设施建设、DevOps、网络数据采集（爬虫）、自动化测试、数据分析、机器学习等领域都有着广泛的应用。
### 代码中的注释
1. 单行注释 - 以#和空格开头的部分
2. 多行注释 - 三个引号开头，三个引号结尾

## Day2		语言元素
#### 指令和程序
1. 计算机的硬件系统通常由五大部件构成，包括：运算器、控制器、存储器、输入设备和输出设备。
2. 中央处理器（CPU）：运算器和控制器放在一起，它的功能是执行各种运算和控制指令以及处理计算机软件中的数据。
3. “冯·诺依曼结构”有两个关键点，一是指出要将**存储设备与中央处理器分开**，二是提出了将数据以**二进制**方式编码。
## 变量和类型
#### 常用的数据类型
- **整型**：Python中可以处理任意大小的整数，而且支持二进制（如`0b100`，换算成十进制是4）、八进制（如`0o100`，换算成十进制是64）、十进制（`100`）和十六进制（`0x100`，换算成十进制是256）的表示法。
- **浮点型**：浮点数也就是小数，之所以称为浮点数，是因为按照科学记数法表示时，一个浮点数的小数点位置是可变的，浮点数除了数学写法（如`123.456`）之外还支持科学计数法（如`1.23456e2`）。
- **字符串型**：字符串是以单引号或双引号括起来的任意文本，比如`'hello'`和`"hello"`,字符串还有原始字符串表示法、字节字符串表示法、Unicode字符串表示法，而且可以书写成多行的形式（用三个单引号或三个双引号开头，三个单引号或三个双引号结尾）。
- **布尔型**：布尔值只有`True`、`False`两种值，要么是`True`，要么是`False`，在Python中，可以直接用`True`、`False`表示布尔值，也可以通过布尔运算计算出来。
- **复数型**：形如`3+5j`，跟数学上的复数表示一样，唯一不同的是虚部的`i`换成了`j`。实际上，这个类型并不常用，大家了解一下就可以了。
