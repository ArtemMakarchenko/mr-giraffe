<template>
  <div class="reviews">
    <router-link
      class="router-link"
      to="/"
    >Home</router-link>
    <h1>Reviews Page</h1>
  </div>
</template>

<script>
export default {
  name: 'Reviews',
};
</script>

<style lang="scss" scoped>
.reviews{
  padding: 30px;
  max-width: 1200px;
  margin: 0 auto;
}
.router-link, h1{
  text-decoration: none;
  font-family: 'Bebas Neue', cursive;
  color: rgb(51, 51, 51);
}
</style>
