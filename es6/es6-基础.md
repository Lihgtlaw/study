# ES6基础学习

ES2015(ES6) 新增加了两个重要的 JavaScript 关键字: **let** 和 **const**。

**let** :声明的变量只在 let 命令所在的代码块内有效。

**const** :声明一个只读的常量，一旦声明，常量的值就不能改变。

```javascript
{
  let a = 0;
  var b = 1;
}
a  // ReferenceError: a is not defined
b  // 1
```

