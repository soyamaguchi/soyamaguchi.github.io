<template>
  <div class="home">
    <span class="job">Software Engineer</span>
    <div class="name">
      <span class="dark">Soya</span>
      Yamaguchi
    </div>
    <Introduction msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Introduction from '@/components/Introduction.vue'

export default {
  name: 'home',
  components: {
    Introduction
  }
}
</script>

<style lang="scss" scoped>
.home {
  margin-top: 5rem;
  .job {
    color: #c2c2c2;
  }
  .name {
    .dark {
      color: #616161;
    }
    margin-top: 0.5rem;
    font-weight: bold;
    font-size: 3rem;
    color: #737373;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }
}
</style>