[toc]

## 简介

1. 设计模式分析
   - 应用场景(设计意图): 不同设计模式的核心区别
   - 解决方案(设计思路 & 代码实现): 只看实现可能会有很多设计模式都类似的想法
2. 设计模式: [为了写出高质量的代码 + 解耦(核心)](../coding/readme.md)
   - 创建型: 对象的创建 + 将创建和使用代码解耦
   - 结构型: 类或对象的组合大结构 + 将不同功能{类}代码解耦, 之后在组合
   - 行为型: 类或对象之间的交互 + 将不同的行为代码{类与对象间}解耦
3. 世间没有什么银弹, 设计模式是对经验的总结: `解耦|复用|扩展`
   - 多是以空间(类数量)换简单(类大小)&扩展性的妥协
   - 得到的销量符合开闭原则、高内聚松耦合等特性, 控制了代码复杂度, 提高扩展性
4. 设计模式是为了解决问题, 而不是找问题

## 分类: **观模中策 访状解命 责迭备**

1. 创建者模式[5]

   - summary: `如何实例化(一个|一组)对象` + 创建复杂对象 & 将对象的创建与使用分离{解耦}

   - **单例模式**
   - **工厂模式**
   - 抽象工厂模式
   - **建造者模式**
   - 原型模式

2. 结构型模式[7]-Wrapper{4}

   - summary: 将类和对象按某种布局组成更大的结构(如果使用对象构建软件组件)

     1. 类结构型模式: 采用继承机制来组织接口和类
     2. **对象结构型模式**: 釆用组合或聚合来组合对象
     3. _代理模式_ & 桥接模式 & 装饰器模式 & 适配器模式: 通过 Wrapper 类二次封装原始类

   - **代理模式**
   - **适配器模式**
   - 桥接模式:
   - 装饰者模式:
   - 外观/门面模式: facade
   - 组合模式
   - 享元模式: flyweight

3. 行为模式[11]

   - summary: 类或对象之间的交互

     1. 对象间的职责分配
     2. 描述类和对象怎样协同完成单个对象无法完成的任务(执行一个行为)

   - **模板方法模式**
   - **策略模式**
   - 迭代器模式
   - 状态模式
   - 责任链模式
   - 命令模式
   - 观察者模式
   - 解释器模式
   - 中介模式
   - 备忘录模式
   - 访问者模式

## UML 图

1. 关联关系

   - 单向关联: →
   - 双向关联: -
   - 自关联

2. 聚合关系: 带空心菱形的实线

   - 老师与学校

3. 组合关系: 带实心菱形的实线

   - 接口和实现类: 头和身体

4. 依赖关系: 带箭头的虚线

   - 局部变量 / 方法的参数/ 对静态方法的调用

5. 继承关系: 带空心三角箭头的实线
6. 实现关系: 带空心三角箭头的虚线

---

## reference

1. https://github.com/Alice52/programming/issues/2
2. [设计模式之美](https://www.aliyundrive.com/drive/folder/62008661f37d5fd3b1df40a38d9108c4234f1dca) + [bak](https://time.geekbang.org/column/intro/100039001)
3. [设计模式讲解-黑马](https://github.com/Alice52/programming/issues/9)
4. [设计模式-尚硅谷](https://www.bilibili.com/video/BV1mG411K7Jj/)
5. [dp-repo real-word explain](./README-CN.md)
6. [uml](https://sbcode.net/typescript/strategy/)
7. [dp](https://refactoringguru.cn/design-patterns/command)
