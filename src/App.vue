<template>
  <!-- 结构 -->
  <div>
    <School></School>
  </div>
</template>
<script>
/*交互内容*/
// 在脚手架里.vue后缀可以省略
import School from "./components/School";

export default {
  name: 'App',
  components: {
    School
  }
}
</script>