# 如何加入翻译

* 1、fork 项目；
* 2、提出 issue ，表明自己想翻译哪些内容，时间大致是多久；
* 3、组织者会审核此 issue ，审核完成后会将 issue 设为“翻译中”状态，此时申请者可以开始翻译了；
* 4、翻译完之后，提交 pull request ，并将相应 issue 修改为“翻译完成”；
* 5、pull request 审核通过后会被合并到 master 分支， issue 状态会被改为 “review 通过”；
* 6、如果在指定时间内还没翻译完，则相应 issue 就会被设为“超时未完成”状态，此时该部分翻译内容可能会被重新分配给其他人。

# 目录

* [关于这本书你需要知道的](./about.md)
    * 本书读者： JavaScript 程序员
    * 为什么应该阅读这本书？
    * 如何阅读这本书
    * 术语和约定
    * 补充
    * 脚注
* 前言
* 感谢

* I 背景
    * 1 关于 ECMAScript 6 （ ES6 ）
        * 1.1 TC39 （ Ecma 技术委员会 39 ）
        * 1.2 ECMAScript 6 是如何设计的
        * 1.3 JavaScript vs ECMAScript
        * 1.4 升级到 ES6
        * 1.5 ES6 的目标
        * 1.6 ES6 特性概览
        * 1.7 ECMAScript 历史简介
    * 2 ECMAScript 6 常见问题解答
        * 2.1 当前引擎支持 ES6 的程度是多少？
        * 2.2 如何将 ECMAScript 5 代码迁移至 ECMAScript 6 ？
        * 2.3 现在学习 ECMAScript 5 还有必要吗？
        * 2.4 ES6 臃肿吗？
        * 2.5 ES6 规范文档不是很大吗？
        * 2.6 ES6 包含了数组吗？
        * 2.7 ES6 是静态类型的吗？
        * 2.8 应该避免使用类吗？
        * 2.9 ES6 有`特性`（ traits ）或者`混入`（ mixins ）吗？
        * 2.10 为什么 ES6 有带 `=>` 的箭头函数，而没有带 `->` 的箭头函数？
        * 2.11 在哪里可以找到更多的 ES6 资源？
    * 3 One JavaScript: avoiding versioning in ECMAScript 6
        * 3.1 版本
        * 3.2 严格模式与 ECMAScript 6
        * 3.3 结论
        * 3.4 深入阅读
    * 4 进入 ECMAScript 6 开发
        * 4.1 现在就使用 ECMAScript 6
        * 4.2 转换工具
        * 4.3 其他有用的 ES6 工具和库
        * 4.4 ES6 交互式解释器（ REPLs ）
        * 4.5 有 ES6 特性不能转换成 ES5 吗？
        * 4.6 示范转换设置
        * 4.7 示范设置：通过 webpack 和 babel 处理客户端 ES6
        * 4.8 示范设置：通过 Babel 在 Node.js 基础上动态转换 ES6
        * 4.9 示范设置：通过 gulp 和 Babel 在 Node.js 上静态转换 ES6
* II 数据
    * 5 [新的数值和 Math 特性](./5.md)
        * 5.1 概览
        * 5.2 新的整型字面量
        * 5.3 新的静态 Number 类属性
        * 5.4 Math
        * 5.5 常见问题解答
    * 6 新的字符串特性
        * 6.1 概览
        * 6.2 Unicode 字符解析（ Unicode code point escapes ）
        * 6.3 字符串插值，多行字符串字面量和原始的字符串字面量
        * 6.4 遍历字符串
        * 6.5 Numeric values of code points
        * 6.6 检查字串包含和重复字符串
        * 6.7 所有新的字符串方法
    * 7 Symbols
        * 7.1 概览
        * 7.2 新的原始类型
        * 7.3 使用 Symbols 来实现一些概念
        * 7.4 Symbol 作为属性的键
        * 7.5 使用 Symbol 跨领域（ Crossing realms with symbols ）
        * 7.6 Symbol 包装器对象（ Wrapper objects for symbols ）
        * 7.7 转换 Symbol 为其他原始类型
        * 7.8 JSON 与 Symbol
        * 7.9 常见问题
        * 7.10 Symbol API
    * 8 模板字面量和标签化模板
        * 8.1 概览
        * 8.2 介绍
        * 8.3 标签化模板使用示例
        * 8.4 实现标签函数（ tag function ）
        * 8.5 常见问题的解答
    * 9 变量与作用域
        * 9.1 概览
        * 9.2 通过 let 和 const 实现块级作用域
        * 9.3 const 创建不可变的变量
        * 9.4 暂时性死区（ temporal dead zone ）
        * 9.5 循环头中的 let 和 const
        * 9.6 参数
        * 9.7 全局对象
        * 9.8 函数声明和类声明
        * 9.9 代码风格：var 还是 let，还是 const
    * 10 [解构](./10.md)
        * 10.1 [概览](./10.1.md)
        * 10.2 [背景：构造数据（对象和数组字面量）和解构数据](./10.2.md)
        * 10.3 [模式](./10.3.md)
        * 10.4 [模式是如何获取到内部的值的？](./10.4.md)
        * 10.5 [如果有一部分没有匹配上](./10.5.md)
        * 10.6 更多对象解构特性
        * 10.7 更多数组解构特性
        * 10.8 不是仅仅能赋值给变量
        * 10.9 解构的陷阱
        * 10.10 解构示例
        * 10.11 解构算法
    * 11 [参数处理](./11.md)
        * 11.1 [概览](./11.1.md)
        * 11.2 [参数解构](./11.2.md)
        * 11.3 [默认参数值](./11.3.md)
        * 11.4 [剩余参数（ Rest parameters ）](./11.4.md)
        * 11.5 [模拟命名参数](./11.5.md)
        * 11.6 [参数解构示例](./11.6.md)
        * 11.7 [编码风格小建议](./11.7.md)
        * 11.8 扩展运算符（...）
* III 模块化
    * 12 ECMAScript 6 中的可调用实体
        * 12.1 ECMAScript 6 中的可调用实体
        * 12.2 风格思考（ Thoughts on style ）
        * 12.3 ECMAScript 5 和 6 中的方法传递和直接调用（ Dispatched and direct method calls in ECMAScript 5 and 6 ）
    * 13 箭头函数
        * 13.1 概览
        * 13.2 传统的函数都是糟糕的非方法的函数
        * 13.3 箭头函数语法
        * 13.4 词法变量
        * 13.5 语法陷阱
        * 13.6 箭头函数与常规函数对比
    * 14 新的包含类的面向对象特性
        * 14.1 概览
        * 14.2 新的对象字面量特性
        * 14.3 新的 Object 类方法
        * 14.4 ES6 中遍历属性键
        * 14.5 常见问题的解答
    * 15 类
        * 15.1 概览
        * 15.2 必要性
        * 15.3 类详解
        * 15.4 子类详解
        * 15.5 通过 JavaScript 代码来解释构造器的调用
        * 15.6 The species pattern
        * 15.7 常见问题的解答
        * 15.8 类的优点和缺点
        * 15.9 深入阅读
    * 16 模块
        * 16.1 概览
        * 16.2 JavaScript 中的模块
        * 16.3 初窥 ES6 模块
        * 16.4 设计目标
        * 16.5 更多关于引入（ import ）和导出（ export ）
        * 16.6 ECMAScript 6 模块加载 API
        * 16.7 在浏览器中使用 ES6 模块
        * 16.8 常见问题的解答
        * 16.9 ECMAScript 6 模块的好处
        * 16.10 深入阅读
* IV 集合
    * 17 新的数组特性
        * 17.1 数组类方法
        * 17.2 数组原型方法
    * 18 Maps 和 Sets
        * 18.1 概览
        * 18.2 Map
        * 18.3 WeakMap
        * 18.4 Set
        * 18.5 WeakSet
        * 18.6 关于 Maps 和 Sets 的常见问题解答
    * 19 类型数组
    * 20 遍历和遍历器
    * 21 生成器（ Gnerators ）
        * 21.1 概览
        * 21.2 什么是生成器？
        * 21.3 作为遍历器的生成器（数据生产）
        * 21.4 作为观察者的生成器（数据消费）
        * 21.5 作为协同器的生成器（多任务协作）
        * 21.6 生成器示例
        * 21.7 在遍历 API 内集成（包括生成器）
        * 21.8 代码风格：空格在星号之前还是之后
        * 21.9 结论
        * 21.10 深入阅读
* V 标准库
    * 22 正则表达式
    * 23 异步编程（后台）
        * 23.1 JavaScript 调用堆栈
        * 23.2 浏览器的事件循环
        * 23.3 异步获取结果
        * 23.4 向前看
        * 23.5 深入阅读
    * 24 用于异步编程的 Promises
        * 24.1 概览
        * 24.2 Promise
        * 24.3 第一个例子
        * 24.4 创建和使用 Promise
        * 24.5 例子
        * 24.6 Promise 链
        * 24.7 组合
        * 24.8 Promise 总是异步的
        * 24.9 备忘单： ECMAScript 6 Promise API
        * 24.10 Promise 的优缺点
        * 24.11 Promise 和生成器
        * 24.12 调试 Promise
        * 24.13 Promise 内部
        * 24.14 两个有用的 Promise 附加方法
        * 24.15 ES6 兼容的 Promise 库
        * 24.16 与传统异步代码对接
        * 24.17 深入阅读
* VI 杂项
    * 25 Unicode
    * 26 尾递归优化
    * 27 用代理实现元编程
        * 27.1 概览
        * 27.2 编程和元编程
        * 27.3 初窥代理（ proxy ）
        * 27.4 代理使用场景
        * 27.5 代理 API 设计
        * 27.6 参考：代理 API
        * 27.8 深入阅读
    * 28 ECMAScript 6 的编码风格
