<template>
  <div>
    <home-header :msg="msg"/>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
export default {
  name: 'Home',
  components: {
    HomeHeader
  },
  data () {
    return {
      msg: 'Hello'
    }
  }
}
</script>

<style lang="stylus" scoped>

</style>
