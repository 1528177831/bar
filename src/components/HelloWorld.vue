<template>
  <div class="hello">
    <h1>{{ msg }}World</h1>
    <infinite-slide-bar :barStyle="{ background: '#fff7cc', padding: '5px 0' }">
      <span style="color: #f60"
        >Your time is limited, so don't waste it living someone else's
        life.</span
      >
    </infinite-slide-bar>
  </div>
</template>

<script>
import InfiniteSlideBar from 'vue-infinite-slide-bar'

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Hello'
    }
  },
  components: {
    InfiniteSlideBar
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  font-weight: normal;
}
</style>
