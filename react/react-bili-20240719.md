# 面试

20240719

## 合成事件

1. 因为浏览器的事件之间存在差别，合成事件可以消除浏览器之间的差异，处理兼容性问题
2. 将事件绑定到最外层，简化事件处理和回收机制，而不是真实的绑定到某个节点上

## hooks 作用

1. 没有之前，组件之间共享状态困难
2. 组件复用困难
3. 代码结构更好理解，出去了this

## useState返回数组不是对象

为了用户可以自定义名字，如果是对象，变量名是写死的，不方便灵活性