<template>
  <div class="about">
    <About />
  </div>
</template>

<script>
import About from '@/components/About.vue'

export default {
  name: 'about',
  components: {
    About
  }
}
</script>

<style lang="scss" scoped>
.about {
    margin-top: 5rem;
}
</style>