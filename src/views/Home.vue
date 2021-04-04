<template>
  <div class="home">
    <NavBar
      :showMenu.sync="showMenu"
    />
    <MobileNavBar
      v-if="showMenu"
      :showMenu.sync="showMenu"
    />
    <Gallery />
  </div>
</template>

<script>
import NavBar from '../components/NavBar.vue';
import Gallery from '../components/Gallery.vue';
import MobileNavBar from '../components/MobileNavBar.vue';

export default {
  name: 'Home',
  components: {
    NavBar,
    Gallery,
    MobileNavBar,
  },
  data: () => ({
    showMenu: false,
  }),
};
</script>
