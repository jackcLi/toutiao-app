<template>
  <div class="layout-container">
    <router-view></router-view>
    <van-tabbar route v-model="active">
      <van-tabbar-item :to="{ name: 'home' }" icon="home-o"
        >首页</van-tabbar-item
      >
      <van-tabbar-item :to="{ name: 'qa' }" icon="comment-o">问答</van-tabbar-item>
      <van-tabbar-item :to="{ name: 'video' }" icon="video-o"
        >视频</van-tabbar-item
      >
      <van-tabbar-item :to="{ name: 'my' }" icon="manager-o"
        >我的</van-tabbar-item
      >
    </van-tabbar>
  </div>
</template>

<script>
export default {
  name: "LayoutIndex",
  data() {
    return {};
  },
  computed: {},
  watch: {},
  methods: {},
  created() {},
  mounted() {},
  beforeCreate() {},
  beforeMount() {},
  beforeUpdate() {},
  updated() {},
  beforeDestroy() {},
  destroyed() {},
  activated() {},
  components: {},
};
</script>

<style lang='scss' scoped>
</style>
