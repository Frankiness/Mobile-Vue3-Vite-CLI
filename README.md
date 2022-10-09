# Vue 3 + Vite + Vant 脚手架

脚手架由 Vue 3 + Vite 搭建。 使用了 Vue 3 `<script setup>` 语法， 点击 [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) 学习 setup 语法。

## 推荐 IDE 和插件

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

## 目录结构

```
├── .vscode // 项目 vscode 插件配置
├── build // 构建相关
├── library // 公共依赖/公共组件 可打包独立组件
├── public // 静态资源 该目录下静态资源应该避免被项目 js 引用
├── src // 源代码
│   ├── apis // 接口请求
│   ├── assets // 图片，字体等静态资源
│   ├── class // 业务类
│   ├── components // 业务组件
│   ├── router // 路由
│   ├── store // 状态管理
│   ├── utils // 项目公共方法
│   └── views // 页面
│   ├── main.js // 入口 加载组件 初始化
│   ├── App.vue // 入口页面
├── .env // 环境变量
├── .eslintrc.cjs // eslint 配置项
├── .prettierrc.cjs // prettier 配置项
├── jsconfig.json // 项目编译器配置选项
├── package.json // 依赖文件
└── vite.config.js // 构建脚本
```
