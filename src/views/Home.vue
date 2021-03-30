<template>
  <div class="home">
    <NavBar />
    <Gallery />
  </div>
</template>

<script>
import NavBar from '../components/NavBar.vue';
import Gallery from '../components/Gallery.vue';

export default {
  name: 'Home',
  components: {
    NavBar,
    Gallery,
  },
};
</script>
