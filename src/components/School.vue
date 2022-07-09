<template>
  <!-- 结构 -->
  <div class="demo">
    <h2>学校名称：{{ name }}</h2>
    <h2>学校地址：{{ address }}</h2>
  </div>
</template>
<script>
/*交互内容*/
export default {
  name: 'ASchool',
  data() {
    return {
      name: 'xx大学',
      address: '北京'
    }
  }
}
</script>
<style>
</style>