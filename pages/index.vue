<template>
  <div class="home">
    <span class="home__job">Software Engineer</span>
    <div class="home__name">
      <span class="home__name--dark">Soya</span>
      Yamaguchi
    </div>
    <Introduction />
  </div>
</template>

<script>
// @ is an alias to /src
import Introduction from '~/components/Introduction.vue'

export default {
  components: {
    Introduction
  }
}
</script>

<style lang="scss" scoped>
.home {
  margin-top: 5rem;
  &__job {
    color: #c2c2c2;
  }
  &__name {
    &--dark {
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
