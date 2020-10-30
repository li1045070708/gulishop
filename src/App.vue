<template>
  <div>
    <Header></Header>
   <router-view></router-view>
    <Foother v-show="!this.$route.meta.isHidden"></Foother>
  </div>
</template>

<script>
import Header from '@/components/Header'
import Foother from '@/components/Foother'

export default {
  name: 'App',
  components: {
    Foother,
    Header
  }
}
</script>

<style>

</style>
