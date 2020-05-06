> 官网: [https://haomo-tech.com](https://haomo-tech.com)

> 作者: 毫末科技

> 邮箱: hxg@haomo-studio.com

## 预览

![预览图片](http://downloads.haomo-tech.com/uniapp/hm-friends-list.png)

[在线效果预览](http://template.uniapp.haomo-tech.com/pages/haomo/test-component/hm-friends-list)

更多毫末科技的uni-app跨端模板，请见[毫末科技uni-app跨端模板](https://haomo-tech.com/sale.html)

## 技术支持

我们公司提供超低价的切图服务哈。移动端平均50元每个页面，PC Web端平均80元每个页面。目前支持出vue、react、uniapp、taro、flutter、小程序代码代码，代码支持自适应。其中uniapp、taro一份代码支持多端。app原生会在五月份开始支持。示例demo: [http://edu.uniapp.haomo-tech.com](http://edu.uniapp.haomo-tech.com)。部分样例代码：[http://downloads.haomo-tech.com/uniapp-demo.zip](http://downloads.haomo-tech.com/uniapp-demo.zip)

* [uni-app插件市场](https://ext.dcloud.net.cn/plugin?id=1390)

* [npm包](https://www.npmjs.com/package/hm-uniapp-friends-list)

* [github地址](https://github.com/haomo-studio/hm-uniapp-friends-list)

* [gitee地址](https://gitee.com/haomo/hm-uniapp-friends-list)

毫末科技将长期迭代本组件。需要技术支持，请进钉钉群：

<img width="250" src="http://downloads.haomo-tech.com/%E6%AF%AB%E6%9C%ABuniapp%E7%BB%84%E4%BB%B6%E6%8A%80%E6%9C%AF%E6%94%AF%E6%8C%81.jpg">

## 概述

毫末uni-app新闻卡片组件。支持H5/小程序(微信、支付宝、头条、百度、QQ)/App；组件可自适应各种屏幕大小的手机。

## 使用

请使用HBuilderX导入组件。

在script中引用：

```javascript
import HmFriendsList from '@/components/hm-friends-list/index.vue'
export default {
    components: {HmFriendsList}
}
```

在template中使用：

```html
<template>
  <div class="test-component">
    <hm-friends-list :options="options"></hm-friends-list>
  </div>
</template>
<script>
import HmFriendsList from '@/components/hm-components/hm-friends-list/index.vue'

export default {
  components: {
    HmFriendsList
    },
  data() {
    return {
      options: {
          friendsList: '朋友表',
          img:
            '/static/hm-friends-list/images/img_24015_0_0.png',
          avator:
            '/static/hm-friends-list/images/img_24015_0_1.png',
          miller: '张三',
          user:
            '/static/hm-friends-list/images/img_24015_0_2.png',
          lingna: '李四',
          word: 'MY',
          tom: '王五',
          userImage:
            '/static/hm-friends-list/images/img_24015_0_3.png',
          than: '黄磊',
          text: 'LW',
          louis: '赵高',
          userImg:
            '/static/hm-friends-list/images/img_24015_0_4.png',
          romi: '罗生'
        }
    };
  },
  methods: {}
};
</script>
<style>
</style>

```

## 属性说明

| 属性名        | 类型     | 默认值 | 说明                                                                       |
|-----------   |---------|--------|----------------------------------------------------------------------------|
| options        | Object  | -      | 卡片属性                                                                   |

options对象各个属性说明如下：

| 属性名        | 类型     | 默认值 | 说明                                                                       |
|-----------   |---------|--------|----------------------------------------------------------------------------|
| friendsList        | String  | -      | 标题                                                                   |
| img        | String  | -      | 图片                                                                   |
| avator        | String  | -      | 图片                                                                   |
| miller        | String  | -      | 姓名                                                                   |
| user        | String  | -      | 图片                                                                   |
| lingna        | String  | -      | 姓名                                                                   |
| word        | String  | -      | 姓名                                                                   |
| tom        | String  | -      | 姓名                                                                   |
| userImage        | String  | -      | 图片                                                                   |
| romi        | String  | -      | 姓名                                                                   |
| louis        | String  | -      | 姓名                                                                   |
| userImg        | String  | -      | 图片                                                                   |
| text        | String  | -      | 姓名                                                                   |
| than        | String  | -      | 姓名                                                                   |


## 事件说明


## 更新日志

### 0.0.1(2020-03-09)

* 完成第一个版本
