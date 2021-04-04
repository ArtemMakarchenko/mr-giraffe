<template>
  <div class="gallery">
    <div class="gallery__item">
      <router-link
        class="router-link"
        to="/work"
      >
        <img src="../assets/img/previews/Adams.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/ALLL.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Bloom.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Brennbygget.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Basilisk.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Cardinal Recovery.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Bond.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/bpf.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Axis.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Brutopia.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Closely.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Cemproof.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Blue Pearl.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/CSE.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/DeMoss.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/dialog.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/doeco.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/dragon.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/Duston.png">
      </router-link>
    </div>
    <div class="gallery__item">
      <router-link
        to="/work"
      >
        <img src="../assets/img/previews/easytryck.png">
      </router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Gallery',
  data: () => ({
  }),
};
</script>

<style lang="scss" scoped>
$gallery__item_width-4-coll: calc(100% / 4);
$gallery__item_width-3-coll: calc(100% / 3);
$gallery__item_width-2-coll: calc(100% / 2);
$gallery__item_width-1-coll: 100%;
$gallery__item_height: calc(#{$gallery__item_width-4-coll} * 25%);
.gallery{
  padding-left: 225px;
  height: 100%;
  display: flex;
  flex-wrap: wrap;
  @media  only screen and (max-width: 768px) {
    padding-left: 0px;
    padding-top: 150px;
  }
  &__item{
    width: $gallery__item_width-4-coll;
    height: $gallery__item_height;
    @media  only screen and (max-width: 1440px) {
      width: $gallery__item_width-3-coll;
    }
    @media  only screen and (max-width: 1024px) {
      width: $gallery__item_width-2-coll;
    }
    @media  only screen and (max-width: 425px) {
      width: $gallery__item_width-1-coll;
    }
    img{
      width: 100%;
      height: 100%;
    }
  }
}

</style>
