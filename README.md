由于此库 sass less 安装遇到问题，所以只看教程，不使用此库

此代码源于：https://github.com/oinsd/Vue.js-Learning-Example/tree/master/NO.27-29_vue-router_%E9%A1%B9%E7%9B%AE%E5%AE%89%E8%A3%85%E4%B8%8E%E4%BD%BF%E7%94%A8_Cli%E8%84%9A%E6%89%8B%E6%9E%B6%E9%A1%B9%E7%9B%AE%E8%B7%AF%E7%94%B1  
来自教程：bilibli Vue.js 极简教学：https://www.bilibili.com/video/BV1bV411r7mg

用于 vue 路由学习，以及作为部署带有路由 router 功能页面的模板

# hello_2

--------------------------------------------常用--------------------------------------------

## ViewUI 安装与引入

### 安装

cnpm install view-design --save

### 引入

import ViewUI from 'view-design';
import 'view-design/dist/styles/iview.css';
Vue.use(ViewUI);

## ElementUI 安装与引入

### 安装

cnpm i element-ui -S

### 引入

import ElementUI from 'element-ui';
import 'element-ui/lib/theme-chalk/index.css';
Vue.use(ElementUI);

## less or sass 安装

若安装了 UI 库后，报 cass 和 less 错误，则以下安装
cnpm install --save sass-loader node-sass
cnpm install --save less-loader node-less

## vue-cli 安装与新建

### cli 安装

cnpm install -g @vue/cli

### cli 查看版本

vue --version

### cli 创建一个项目

vue create hello-world

## vue-router 安装与使用

### vue-router 安装

cnpm install vue-router

### vue-router 使用

import VueRouter from 'vue-router'
Vue.use(VueRouter)
<router-view></router-view>
<router-link>

--------------------------------------------项目安装--------------------------------------------

## Project setup

```
cnpm install
```

### Compiles and hot-reloads for development

```
cnpm run serve
```

### Compiles and minifies for production

```
cnpm run build
```
