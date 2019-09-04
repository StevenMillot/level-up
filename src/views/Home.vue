<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <UserAuth msg="Welcome to the Future"/>
  </div>
</template>

<script>
import UserAuth from '@/components/UserAuth.vue'

export default {
  name: 'home',
  components: {
    UserAuth
  }
}
</script>

<style lang="scss">
  body { font-size: 62.5%; }
</style>
