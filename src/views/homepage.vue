<template>
  <div class="homepage">
    <!-- 侧边栏 -->
    <sidebar/>
    <!-- 头部 -->
    <topbar/>
    <!-- 主体区 -->
  </div>
</template>

<script>
import sidebar from '@/components/sidebar/sidebar'
import topbar from '@/components/topbar/topbar'
export default {
  name: 'homepage',
  data () {
    return {

    }
  },
  components: {
    sidebar, topbar
  }
}
</script>

<style scoped lang="less">
.homepage{
  position: relative;
  height: 100%;
}
</style>
