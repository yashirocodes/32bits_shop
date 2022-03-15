<template>
  <div>
    <NavBar/>
  </div>
  <router-view/>
</template>
<script>
import NavBar from '@/components/NavBar'
export default {
  components:{
    NavBar,
  }
}
</script>
<style>

</style>
