# 01-字节实习-20220508
## 一面
1. 前端权限管理是怎么做的？
3. 尾递归和递归有什么区别？
4. jwt和cookie的区别？
5. webpack的打包优化做了什么？
6. tree-shaking为什么能知道哪些代码可以被消除掉？
7. 有没有对项目进行一些性能优化的测试
8. http优化，分包策略
9. 防抖和节流是什么，用在什么场景？
10. 如果让你来设置防抖和节流api，你会提供一些什么功能？
11. 项目前后端是怎么进行交互的
12. xss，csrf是什么，怎么防范？
13. 大数相加，大数相乘

## 二面
1. vue diff算法
2. 如果要你实现一个最长递增子序列的算法你会怎么实现？
3. computed是怎么实现的？
4. 如何收集依赖的
5. proxy有哪些参数，怎么用的，知道proxy的第三个参数吗？
6. 知道Reflect吗，Reflect能做什么
7. 项目中遇到了哪些比较困难的问题
8. 浏览器缓存
9. webpack打包做了哪些优化?
10. tree-shaking的是怎么做到删除没用的代码?(基于esm)
11. esm和commonjs有什么区别
12. loader和plugin的区别
13. 事件循环
14. 浏览器有哪些线程
15. 为什么js线程和网络线程要分开，不能在一个线程中吗？
16. 看代码说输出结果(promise，setTimeout，async await)
17. 实现一个flat函数。实现后，面试官说增加可以传入扁平层次功能。
18. 实现一个promise.all
19. 实现一个isEqual函数。对比两个对象，如果这两个对象看起来一样那就返回true，如果不一样就返回false
```
const obj1 = {name:'aaa',friends:[1，2，3]}
const obj2 = {name:'aaa',friends:[1，2，3]} 
isEqual(objl，obj2) //true 
obj1 === obj2 // false
```
## 三面
1. diff算法 
2. computed 
3. vue3的优化 
4. nextTick
5. 二叉树层序遍历
6. {{name}}很开心，{{name}}今年{{age}}岁->小明很开心，小明今年18岁。const obj={name:'小明'，age:18}根据key替换value
7. 数字签名有什么用，会不会被伪造？
