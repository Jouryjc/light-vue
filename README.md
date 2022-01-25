# vue-mini-pro

> 实现一个极简的 vue3.x，直接阅读源码是枯燥无味的。熟悉基础使用之后，带着自己的理解去实现它，过程中有卡壳的地方再去阅读源代码，这样的收获无疑是最大的。

## Features
1. 使用 pnpm + workspace 实现 monorepo
2. 使用 vitest 做测试框架

## 通过简单的例子结合图文去讲解每一个模块的原理

- 从入口看技术栈、全局
  - package.json
  - pnpm
  - scripts
- reactivity
  - ref
  - reactive
  - effect
  - 其他 API
- compiler
  - parser -> AST
  - optimize、transform
  - genCode
- 组件的实现
  - 跟普通元素的区别
- 渲染 render
- 其他特性的原理
  - 作用域插槽、具名插槽
  - props
  - teleport
  - provide/inject
  - 。。。
- 其他插件（核心特性）
  - vue-router（导航守卫、基础API）
  - pinia