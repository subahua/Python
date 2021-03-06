#### Java诞生
- 1900年，Sun公司预料嵌入式系统将在未来的家电领域大展身手，决定编写一个通用控制系统。
- 1995年，Sun公司发布了Java语言.
#### Java的基础知识
- Java是一种纯粹的面向对象的程序设计语言，一次Java程序必须以类（class）的形式存在，类（class）是Java程序的最小单位。
- Java解释器规定：如果某个类能直接被解释执行，则这个类必须包含main方法，而且main方法必须使用 public static void 来修饰，且main方法的形参必须是字符串数组类型(String[] args)，即main的写法几乎固定。
#### 面向过程与面向对象的区别
- 事件：猪八戒吃西瓜
- 在面向过程的程序世界里，一切以函数为中心，函数最大，因此这件事情会用如下语句来表达：
- 吃（猪八戒，西瓜）
- 在面向对象的程序世界里，一切以对象为中心，对象最大，因此这件事情会用如下语句来表达：
- 猪八戒.吃（西瓜）

#### JAVA API文档
- 文档注释以斜线后紧跟两个星号开始，以星号后紧跟一个斜线结束，中间部分全部都是文档注释，会被提取到API文档中。

- Java9 API文档支持HTML5规范。
```
javadoc 选项 Java源文件:包
javadoc -d<directory>:该选项指定一个路径，用于将生成的API文档放到指定目录下。
javadoc -windowtitle<text>:该选项指定一个字符串，用于设置API文档的浏览器窗口标题。
javadoc -doctitle<html-code>:该选项指定一个HTML格式的文本，用于指定概述页面的标题。
javadoc -header<html-conde>:该选项指定一个HTML格式的文本，包含每个页面的页眉。
常用的javadoc标记:
@author:指定Java程序的作者
@version:指定源文件的版本
```