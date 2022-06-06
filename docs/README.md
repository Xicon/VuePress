---
home: true

# Public 文件路径

heroImage: /images/hero.png

actions:

- text: 快速上手
  link: /zh/guide/getting-started.html
  type: primary
- text: 项目简介
  link: /guide/
  type: secondary

features:

- title: 简洁至上
  details: 以 Markdown 为中心的项目结构，以最少的配置帮助你专注于写作。
- title: Vue 驱动
  details: 享受 Vue 的开发体验，可以在 Markdown 中使用 Vue 组件，又可以使用 Vue 来开发自定义主题。
- title: 高性能
  details: VuePress 会为每个页面预渲染生成静态的 HTML，同时，每个页面被加载的时候，将作为 SPA 运行。

---

# 个人简历

## 个人介绍

- name: 李夏 (LisaSummer)
- age: 20
- school: [澳门大学](https://www.um.edu.mo/)

## 教育背景

**专业课:**

1. C#面向对象
2. 计算机基础
3. 高等数学
4. 三维动画建模
5. HTML5网页设计与制作
6. 移动UI界面构成与图标设计
7.

## 前端部分

1. **开发框架**: 主要使用[Vue-TS](https://cn.vitejs.dev/guide/#browser-support)进行开发

2. **Javascript**: 主要使用[Typescript](https://www.typescriptlang.org/),`ES2015+`相结合进行开发

3. **工具部分**: 使用`Vue`周边相关的工具([Vite](https://cn.vitejs.dev/),[Vue-Router](https://router.vuejs.org/)
   ,[Vue-i18n](https://kazupon.github.io/vue-i18n/zh/introduction.html),[Pinia](https://pinia.vuejs.org/))进行开发.

> 不使用Vuex的原因: 使用`Typescript`对`Vuex`进行类型限制比较麻烦,`Vuex`的`Mutation`显得有点多余,`Pinia`更契合`Javascript`的开发方式

4. **脚手架**: 基本只用[Vite,](https://cn.vitejs.dev/)少量使用[Vue-CLI](http://cli.vuejs.org/)
   只有简单使用过[wabpack](https://webpack.js.org/)

> 不使用`wabpack`原因: 笨重,沉余, 性能没有`Vite`快

5. **CSS**: 主要使用`SASS`的`SCSS`模式进行开发, 也使用`Stylus`,简单使用过`Tailwind CSS`

6. **Test**: 主要使用[Mocha](https://mochajs.org/)作为测试框架, [chai](https://www.chaijs.com/)作为`Mocha`测试框架`断言`
   的补充, [sinon](https://sinonjs.org/)作为单元测试, [nyc](https://github.com/istanbuljs/nyc)作为测试时的覆盖率测试

7. **MockData**: 可以搭建`Node`服务器进行网络请求数据, 也可以使用前端的工具库([mockjs](https://github.com/nuysoft/Mock/wiki/Getting-Started)
   ,[fakejs](https://github.com/faker-js/faker),[json-server](https://github.com/typicode/json-server))来进行模拟生成数据,
   使用[Apifox](https://www.apifox.cn/)与[Apipost](https://www.apipost.cn/)工具进行接口测试
8. **开发工具部分**: 使用[Webstorm](https://www.jetbrains.com/zh-cn/webstorm/)进行日常开发,
   使用[DataGrip](https://www.jetbrains.com/zh-cn/datagrip/)进行数据库操作, 使用[IDEA](https://www.jetbrains.com/zh-cn/idea/)
   来开发`Spring`,少量使用[VSCode](https://code.visualstudio.com/)与[HBuilder X](https://dcloud.io/hbuilderx.html)来开发

9. **PackageManage**: 主要使用基于[npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm/)
   作为基础的[pnpm](https://pnpm.io/)来作为[npm](https://www.npmjs.com/)包模块的管理, 也可以使用[yarn](https://yarnpkg.com/),[npm]()
   ,[ni](https://www.npmjs.com/package/@antfu/ni)

10. **VersionManage**: 使用`Git`对项目进行管理,使用`nvm`工具对`node`版本进行管理

### Vue生态

1. Vue3.x : 日常主要使用[Vue3.x](https://v3.cn.vuejs.org/)版本的[setup语法糖](https://v3.cn.vuejs.org/api/sfc-script-setup.html)
   进行开发, 很少使用`Vue2.x`版本
2. Vite@next: 使用稳定版, 会配置与其他工具进行开发,打包
3. Vue-Router@next: 单页面路由配置
4. Pinia@next: 存储全局变量
5. Vue-i18n@next:  国际化,本地化翻译
6. Typescript, 加强类型检测,更安全的开发

### CSS框架/预处理器

1. `Sass/Scss`: 日常`Vue`开发时使用
2. `Stylus`: 快速开发`CSS`时用到
3. `Tailwind CSS:`  CSS框架, 使用`Weboack`作为工具开发时使用过

### 可视化平台

1. echarts: 图表

### UI

1. element-plus: 页面样式

### 测试/质量/性能

1. `Mocha`: 测试框架
2. `Chai`:  断言库
3. `ts-mocha`:  支持ts文件的mocha测试
4. `sinon`:  单元测试
5. `nyc`:   覆盖率测试
7. `@types/node` : `node`的语法/类型检查
8. `@types/mocha`: `mocha`测试框架的语法/类型检查
9. `@types/chai`: `chai`断言库的语法/类型检查

## 后端部分(简单接触)

1. `Node.js` (`Experss`): 搭建简单的服务器, 前端通过`axios`,`fetch` 连接
2. `Spring`
3. `Python` :  基本知识, 会简单生成图形
4. `MySQL` / `OracleDatabase` / `Mybaits`:  简单的增删改查
5. `Linux` :  搭建`CentOS` 环境, 部署本地前端项目到线上服务器上,通过`nginx`部署到服务器并展示项目

## Dosktop

1. `Tauri`:  将前端项目整合到Windows PC 桌面端

## 规范/规则/约束

1. `stylelint`:  样式规范, 使用`stylelint-config-standard`规范
2. `eslint`: `Javascript`的代码风格

## 加分项

1. `Docker`:  搭建本地的CentOS模拟线上服务器, 本地`Shell`连接进行开发
2. `Shell`: 熟悉常见的`Shell`操作

---

![备案号](./.vuepress/public/备案图标.png)桂ICP2022004535号
---