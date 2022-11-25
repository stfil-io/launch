<template>
  <div>
    <i-header/>
    <router-view/>
    <i-footer></i-footer>
  </div>
</template>
<script>
import IHeader from '@/components/header/IHeader'
import IFooter from '@/components/footer/IFooter'
export default {
  name: 'App',
  components: {
    IHeader,
    IFooter
  }
}
</script>
<style lang="scss">

</style>
