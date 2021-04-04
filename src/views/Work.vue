<template>
  <div class="work">
    <router-link
      class="router-link"
      to="/"
    >Home</router-link>
    <h1>Work Page</h1>
  </div>
</template>

<script>
export default {
  name: 'Work',
};
</script>

<style lang="scss" scoped>
.work{
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
