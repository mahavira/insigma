## 开发\(生产\)环境搭建

* 模块化开发
* 本地预览\实时预览（热更新）
* CSS预编译
* ES6/ES7 编程风格
* 代码规范及错误检查（ESLint）
* API 请求代理
* 代码压缩
* 浏览器前缀（autoprefixer）
* 按需加载（代码拆分）

## 系统基础布局

#### `<Header>`通栏：

* [x] 当前用户 （用户头像/退出/设置）
* [x] 切换子系统
* [x] 站内消息

#### `<Nav>`导航栏：

根据权限显示用户菜单

#### `<Main>`业务模块栏

![](/assets/1.png)

## 通用库

* 页面消息提示
* 日志处理
* 权限控制管理
* 用户信息管理
* 页面管理（跳转到页/切换页面/销毁页面/）
* 数据共享管理
* 本地数据读写管理

## 组件库

> 除使用了开源的第三方UI组件库以外，还封闭了常用的自定义组件  
> 可组合各组件快速构建应用

## 代码规范及约束

> 遵守 Prettier 规范
>
> [https://github.com/prettier/eslint-config-prettier](https://github.com/prettier/eslint-config-prettier)

## 技术栈

* 开发环境：node
* 开发框架：vue + \(vuex/vue-router/axios/rxjs\)
* UI组件库：iview
* 样式预编器: Stylus
* 代码规范: ESLint/Prettier风格

## 开发文档



