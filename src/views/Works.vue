<template>
    <div class="works">
        <Achievement />
    </div>
</template>

<script>
import Achievement from '@/components/Achievement.vue'

export default {
  name: "Works.vue",
  components: {
      Achievement
  }
}
</script>

<style lang="scss" scoped>
.works {
    margin-top: 5rem;
}
</style>