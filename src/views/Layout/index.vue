<template>
  <div>
    <router-view class="main" />

    <van-tabbar route>
      <van-tabbar-item replace to="/home" icon="home-o"
        >首页
        <template #icon>
          <i class="toutiao toutiao-shouye"></i>
        </template>
      </van-tabbar-item>
      <van-tabbar-item replace to="/video" icon="search"
        >视频<template #icon> <i class="toutiao toutiao-shipin"></i> </template
      ></van-tabbar-item>
      <van-tabbar-item replace to="/question" icon="home-o"
        >问答<template #icon> <i class="toutiao toutiao-wenda"></i> </template
      ></van-tabbar-item>
      <van-tabbar-item replace to="/my" icon="search"
        >我的<template #icon> <i class="toutiao toutiao-wode"></i> </template
      ></van-tabbar-item>
    </van-tabbar>
  </div>
</template>

<script>
export default {
  created () { },
  data () {
    return {}
  },
  methods: {},
  computed: {},
  watch: {},
  filters: {},
  components: {}
}
</script>

<style scoped lang="less">
.toutiao {
  font-size: 40px;
}
/deep/.van-tabbar-item__text {
  font-size: 20px;
}
.main{
  padding-bottom: 100px;
  background: #F5F7F9;
}
</style>
