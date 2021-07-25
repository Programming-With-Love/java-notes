# Java学习笔记
<center>

</center>
<br>
<div align="center">
    <img src="https://img.shields.io/badge/JVM-底层原理-blue">
    <img src="https://img.shields.io/badge/JavaSE-基础-yellow">
    <img src="https://img.shields.io/badge/Spring-源码解析-green">
    <img src="https://img.shields.io/badge/Redis-知识整理-red">
    <img src="https://img.shields.io/badge/计算机网络-分层概述-purple">
    <img src="https://visitor-badge.glitch.me/badge?page_id=shaoxiongdu.java-notes">

<h3><a href="https://shaoxiongdu.github.io/java-notes/#/" target="_blank">在线站点（阅读体验更好）</a></h3>
</div>

## 总览
![java-notes](images/java-notes.png)

## 清单

---

### 【JVM】

#### 1. 类加载子系统

- [1-类加载子系统概述](./JVM/01-类加载子系统/01-类加载子系统.md)
- [2-类加载过程](./JVM/01-类加载子系统/02-类加载过程.md)
- [3-类加载器分类](./JVM/01-类加载子系统/03-类加载器的分类.md)
- [4-类加载器的常用方法](./JVM/01-类加载子系统/04-类加载器的常用方法.md)
- [5-双亲委派机制](./JVM/01-类加载子系统/05-双亲委派机制.md)
- [6-沙箱安全机制](./JVM/01-类加载子系统/06-沙箱安全机制.md)

#### 2.  运行时数据区

- [1-运行时数据区的内部结构](./JVM/02-运行时数据区/01-运行时数据区内部结构.md)
- [2-程序计数器(PC寄存器)](./JVM/02-运行时数据区/02-程序计数器(PC寄存器).md)
- [3-虚拟机栈](./JVM/02-运行时数据区/03-虚拟机栈.md)
- [4-本地方法接口](./JVM/02-运行时数据区/04-本地方法接口.md)
- [5-本地方法栈](./JVM/02-运行时数据区/05-本地方法栈.md)
- [6-堆](./JVM/02-运行时数据区/06-堆.md)
- [7-方法区](./JVM/02-运行时数据区/07-方法区.md)
- [8-对象的实例化内存布局与访问定位+直接内存](./JVM/02-运行时数据区/08-对象的实例化内存布局与访问定位+直接内存.md)
- [9-字符串常量池](./JVM/02-运行时数据区/09-字符串常量池.md)

#### 3. 执行引擎

- [1-执行引擎](./JVM/03-JVM执行引擎/JVM执行引擎.md)

#### 4. 垃圾回收机制
- [1-概述](./JVM/04-垃圾回收机制/01-垃圾回收概述.md)
- [2-常见算法](./JVM/04-垃圾回收机制/02-垃圾回收相关算法.md)
- [3-垃圾回收相关概念](./JVM/04-垃圾回收机制/03-垃圾回收相关概念.md)
- [4-垃圾回收器](./JVM/04-垃圾回收机制/04-垃圾回收器.md)

#### 5. 性能优化与调优

- [1-性能优化概述](./JVM/05-性能优化/01-性能优化概述.md)
- [2-JVM监控及诊断工具-命令行篇](./JVM/05-性能优化/02-JVM监控及诊断工具-命令行篇.md)
- [3-JVM监控及诊断工具-GUI篇](./JVM/05-性能优化/03-JVM监控及诊断工具-GUI篇.md)
- [4-JVM运行时参数](./JVM/05-性能优化/04-JVM运行时参数.md)
- [5-分析GC日志](./JVM/05-性能优化/05-分析GC日志.md)

---

### 【Java设计模式】

#### [1.类和类之间的关系(首先了解)](./设计模式/类和类之间的关系(UML图)/类和类之间的关系.md)

#### 2.软件设计七大原则（由浅至深）

| 设计原则            | 简要描述|
| ------------------- | ------------------------------------------ |
| [1. 单一职责原则](./设计模式/单一职责原则/单一职责原则.md)     | 一个类或者一个方法只做一件事情|
| [2. 开闭原则](./设计模式/开闭原则/开闭原则.md)         | 对扩展开发，对修改关闭|
| [3. 接口隔离原则](./设计模式/接口隔离原则/接口隔离原则.md)     | 使用多个专门的接口，而不是总接口 |
| [4. 依赖倒置原则](./设计模式/依赖倒置(转换)原则/依赖倒置（转换）原则.md)     | 面向抽象（接口）编程,而不是面向实现编程|
| [5. 里氏替换原则](./设计模式/里氏替换原则/里氏替换原则.md)     | 所有使用父类对象的地方，都应该可以透明的替换为子类的对象|
| [6. 迪米特法则](./设计模式/迪米特法则/迪米特法则.md)       |一个类应该对其他类保持最少的了解|
| [7. 组合优于继承原则](./设计模式/组合优于继承原则/组合优于继承原则.md) | 多使用`关联`，少使用甚至不使用`继承`来达到复用已有对象的目的 |

#### 3.常见的设计模式 （非全部27种）

| 设计模式|
| -----------------|
| [01-简单工厂模式](./设计模式/01-简单工厂模式/简单工厂模式.md)|
| [02-工厂方法模式](./设计模式/02-工厂方法模式/工厂方法模式.md)|
| [03-抽象工厂模式](./设计模式/03-抽象工厂模式/抽象工厂模式.md)|
| [04-原型模式](./设计模式/04-原型模式/原型模式.md)|
| [05-建造者模式](./设计模式/05-建造者模式/建造者模式.md)|
| 正在更新!|

---

### 【Spring】

-  [注解开发](./Spring/注解开发.md)
-  [IoC容器源码解析](./Spring/Spring容器源码解析.md)

---

### 【计算机网络】

-  [计算机网络概论](./计算机网络/计算机网络概论.md)
-  [计算机网络体系结构](./计算机网络/计算机网络体系结构.md)
-  [网络层详解](./计算机网络/网络层详解.md)
-  [传输层&运输层详解](./计算机网络/传输层&运输层详解.md)

---

### 【Redis】

-  [基本数据类型及常用命令](./Redis/redis基本数据类型及常见命令.md)
-  [redis5新增数据类型](./Redis/redis5新增数据类型.md)


---


## 反馈及改进

如果您在学习的时候遇到了任何问题，或者清单有任何可以改进的地方，

非常欢迎提出`issues`,看到就会回馈.并且将您添加到项目贡献者列表中。

## 参与贡献（非常欢迎！）

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request，填写必要信息。
5. 等待审核即可。通过之后会邮件通知您。

## 许可证

在 MIT 许可下分发。有关更多信息，请参阅[`LICENSE`](./LICENSE)。

## 致谢

>  1. 感谢BiliBili提供的在线课程平台 [BiliBili官网](https://www.bilibili.com)
>  2. 感谢JetBrains提供的配套开发环境许可证 [JetBrains官网](https://www.jetbrains.com/)
>  3. 感谢Gitee提供的图床平台 [图床地址](https://gitee.com/ShaoxiongDu/imageBed)

## 更多开源项目推荐

#### 我的公众号 【Github推荐】 持续分享好玩，有趣，又沙雕的开源项目!   欢迎关注 !

> ![Github推荐](https://gitee.com/ShaoxiongDu/imageBed/raw/master/GithubShareQR.jpg)


