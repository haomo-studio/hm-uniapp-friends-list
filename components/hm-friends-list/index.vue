<template>
  <div class="hm-friends-list">
    <div class="firendClass">
      <div class="hd">
        <text class="friendsList">{{ options.friendsList }}</text>
        <image class="img" :src="options.img" />
      </div>
      <div class="bd">
        <div class="col1">
          <image class="avator" :src="options.avator" />
          <text class="miller">{{ options.miller }}</text>
        </div>
        <div class="col2">
          <image class="user" :src="options.user" />
          <text class="lingna">{{ options.lingna }}</text>
        </div>
        <div class="col3">
          <div class="wrap">
            <text class="word">{{ options.word }}</text>
          </div>
          <text class="tom">{{ options.tom }}</text>
        </div>
      </div>
      <div class="main">
        <div class="headClass">
          <image class="userImage" :src="options.userImage" />
          <text class="than">{{ options.than }}</text>
        </div>
        <div class="portraitClass">
          <div class="block">
            <text class="text">{{ options.text }}</text>
          </div>
          <text class="louis">{{ options.louis }}</text>
        </div>
        <div class="userClass">
          <image class="userImg" :src="options.userImg" />
          <text class="romi">{{ options.romi }}</text>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HmFriendsList',
  props: {
    dataId: {
      type: String,
      default: 'hm-friends-list'
    },
    options: {
      type: Object,
      default: function() {
        return {
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
        };
      }
    }
  },
  data() {
    return {};
  },
  methods: {}
};
</script>
<style>
@import './index.response.css';
</style>
