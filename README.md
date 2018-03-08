# kotlin
### 编程注解规范
### @author 说明类或接口作者
### @deprecated 说明类和接口或成员已经废弃
### @param 说明函数参数
### @return 说明返回值
### @see 参考另一个主题链接
### @exception 说明函数所抛出的异常类
### @throws 同@exception 标签
### @version 类或接口的版本

#Kotlin的编程中使用的，命名规范是骆驼峰的命名的方式，类和文件的名字是首字母大写，方法和属性以小写字母开始

#代码的注释一般采用 // 或者多行注册 /*...*/ 的方式

### TODO 说明此处有待处理的任务，或者代码没有编写完成
### FIXME说明此处代码是错误的，需要修正

### Kotlin中变量声明是一行一个，方便注释
### 尽量使用类型自推到的方式

var level: Long

###语句 没有返回值的代码 while do -while
###表达式有返回值得代码块 1+1 ，if ，when
