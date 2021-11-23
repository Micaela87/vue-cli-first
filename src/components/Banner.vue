<template>
  <div id="banner">
    <Title msg="La mia prima app con Vue CLI!" />
  </div>
</template>

<script>
import Title from './Title.vue';
export default {
  name: 'Banner',
  components: {
    Title
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
 #banner {
   display: flex;
   align-items: center;
   justify-content: center;
   width: 100%;
   height: 500px;
   background-image: url('../assets/coastal-wash-web.jpg');
   background-repeat: no-repeat;
   background-size: cover;
   background-position: center;
 }
</style>