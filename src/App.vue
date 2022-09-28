<template>
  <div id="app">
    <Navbar/>
    <router-view/>
  </div>
</template>
<script>
  import Navbar from '@/components/Navbar.vue'
export default {
  components:{
    Navbar
  }
}
</script>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@200;300;400;500;600;700;800;900;1000&family=Red+Hat+Display:wght@300;400;500;600;700;800;900&display=swap');
html{
  font-family: 'Nunito', sans-serif;
  font-family: 'Red Hat Display', sans-serif;
}

</style>
