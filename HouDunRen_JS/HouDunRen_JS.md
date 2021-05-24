# 第一章 走进 JAVASCRIPT 黑洞

## 5.前端访问流程基本分析

![image-20210522235637207](C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20210522235637207.png)

## 6.注释与执行符

略

## 7.变量声明的基本知识

略

## 8.体验解析过程和变量提升

var会s变量提升

不要使用var,而是使用let和const代替。

## 9.let&const和暂时性死区TDC

let和const先声明，后使用。

否则会有暂时性死区，报错.

## 10.var-let-const的共同点

块级作用域可以访问外部,外部不能访问内部

## 11.可怕的全局污染

一定要声明变量，防止全局污染

严格模式下，不声明会报错

## 12.块作用域这个先进的特性

限制作用域的方法:

旧方法：立即执行函数

新方法：一对花括号

## 13.const 常量声明一探究竟

在同一个作用域里，用const声明的常量不能更改或重复声明

实质:不能修改对内存地址的引用

则const声明的对象，可以改变其属性

## 14.window全局对象污染与重复声明

在全局作用域用var声明的变量会自动添加给window对象，容易造成window全局对象污染。推荐使用let,则不会出现这个问题

var重复声明不报错，同一作用域里，const和let不能重复声明

## 15.object.freeze冻结变量

const不能完全冻结

可以用object.freeze()方法，非严格模式下会静默失败，严格模式下会报错

## 16.标量与引用类型的传值和传址特性

![image-20210523111513534](C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20210523111513534.png)



<img src="C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20210523111528866.png" alt="image-20210523111528866" style="zoom: 33%;" />

## 17.null与undefined详解

undefined:未定义

null:空

## 18.use strict严格模式高质量代码守卫

严格模式从当前作用域及其子作用域受影响

使用严格模式较好。



# 第二章 JavaScript 运算符与流程控制

## for循环可以加标签

label:for(){

breeak label;

}

实践中较少使用



# 第三章 JavaScript值类型使用

## 1.章节介绍与类型判断

判断类型:

typeof:
instanceof:原型链上是否有这个属性

## 2.字符串转义与模板字面量使用

模板字面量:
`

x=:${x}

`

## 

