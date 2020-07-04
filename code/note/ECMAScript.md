ECMAScript 2015 (JavaScript是ECMAScript的扩展语言 Promise在任务队列中属于微任务)

1. let有块级作用域  let不会变量提升  const 声明只读常量

2. 数组解构 三个点剩余参数只能在最后位置上使用  
   对象的解构 不要有相同的命名会产生冲突

3. 模版字符串 使用反引号 支持换行 可以在值中嵌入 
   标签函数；先定义再使用

4. 字符串扩展方法 startWith endWith include 

5. 参数默认值 带有默认值在参数最后

6. 剩余参数 可替代arguments 只出现在最后一位只能使用一次
   展开操作符 

7. 箭头函数 ()=>{}  简化代码简化回调函数的编写  
   不会改变this的指向  指向当前作用域

8. 对象字面量 可以使用表达式的值

9. 对象扩展方法 Object.assign 后面对象的属性的覆盖第一个的
   Object.is 

10. Object.defineProperty 监视某个对象的属性读写 可以捕获属性的读写过程 Proxy代理（监视对象读写过程）
    Object.defineProperty 方法:
    get(监视对象的访问，接收两个参数 代理对象和外部访问的属性名) set(监视对象的设置，三个参数 代理目标对象 属性名称属性值)
    Proxy 对比 Object.defineProperty  
    Object.defineProperty  只能监视属性的读写  
    Proxy 能监视到更多的对象操作  更好的支持数组的监视 重写数组的操作方法 以非侵入的方式监管对象的读写

11. Reflect 属于一个静态类 内部封装了一系列对对象的底层操作 成员方法是Proxy处理对象的默认实现  提供了一套用于操作对象的API
   
12. Promise 解决了传统异步编程中回调函数嵌套过深的问题

13. class类  

14. 静态方法 static 内部直接return this是当前的类型

15. 类的继承 extends 

16. Set 数据结构  去重

17. Map 数据结构 键值对 可以用任意类型作为键

18. Symbol 独一无二的值 最主要的作用就是为对象添加一个独一无二的属性名
    获取Symbol属性名 getOwnPropertySymbol

19. for of 循环 作为遍历所有数据结构的统一方式  break可以终止遍历  
    实现Iterable接口是for of 的前提  iterator.next() 迭代数据
    迭代器模式 

20. 生成器 避免异步编程回调函数的嵌套过深 提供更好的异步编程解决方案 实现了iterator接口

21. ES2016 includes 检查数组中属否存在某个指定元素                   指数运算符 

22. ES2017 entries  返回键值对  getOwnPropertyDescription 获取对象中的属性的描述信息   padStart padEnd  尾逗号  Async Await 异步 