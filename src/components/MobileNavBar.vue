<template>
  <nav class="mobile-nav-bar">
    <div class="cross"
      @click="$emit('update:showMenu', !showMenu)"
    />
    <ul>
      <li>
        <router-link
          to="/"
          class="active"
        >
          DESIGNS
        </router-link>
      </li>
      <li>
        <router-link
          to="/reviews"
        >
          REVIEWS
        </router-link>
      </li>
      <li>
        <router-link
          to="/contact"
        >
          CONTACT
        </router-link>
      </li>
      <li>
        <router-link
          to="/about"
        >
          ABOUT
        </router-link>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'MobileNavBar',
  props: ['showMenu'],
};
</script>

<style lang="scss" scoped>
.cross{
  width: 35px;
  height: 3px;
  background-color: #fff;
  position: absolute;
  top: 75px;
  right: 32px;
  transform: rotate(45deg);
  position: absolute;
  cursor: pointer;
  &::after{
    content: '';
    width: 35px;
    height: 3px;
    background-color: #fff;
    position: absolute;
    transform: rotate(90deg);
  }
}
  .mobile-nav-bar{
    height: 100vh;
    width: 100%;
    background-color: #000;
    color: #fff;
    position: absolute;
    top: 0;
    left: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    ul{
      padding: 0;
      list-style: none;
      z-index: 11;
    }
    li{
      margin-bottom: 40px;
      font-family: 'Bebas Neue', cursive;
    }
    a{
      font-size: 20px;
      color: #454545;
      text-decoration: none;
      transition: color 0.5s;
      &:hover{
        transition: color 0.5s;
        color: #fff;
      }
      &.active{
        color: #fff;
      }
    }
  }
</style>
