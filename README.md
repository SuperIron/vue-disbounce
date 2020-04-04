# vue-disbounce

## 概述

`vue-disbounce`是一款基于`Vue.js`的自定义组件，可以有效避免触发`h5`页面在`ios`浏览器内置的下拉`bounce`效果。

## 安装

`npm i vue-disbounce`

## 配置

| 属性             | 说明               | 类型   | 必填 | 可选值 | 默认值  |
| ---------------- | ------------------ | ------ | ---- | ------ | ------- |
| background-color | wrapper 的背景颜色 | String | 否   | -      | #ffffff |

## 调用

```html
<template>
    <VueDisbounce id="app">
        <!-- 如果有使用路由， -->
        <router-view />
    </VueDisbounce>
</template>

<script>
    import VueDisbounce from "vue-disbounce";

    export default {
        components: {
            VueDisbounce
        }
    };
</script>
```

## 作者

SuperIron
