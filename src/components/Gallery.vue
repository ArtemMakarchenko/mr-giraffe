<template>
  <div class="gallery">
    <div class="gallery__item">
      <img src="../assets/img/previews/Adams.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/ALLL.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Bloom.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Brennbygget.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Basilisk.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Cardinal Recovery.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Bond.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/bpf.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Axis.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Brutopia.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Closely.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Cemproof.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Blue Pearl.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/CSE.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/DeMoss.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/dialog.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/doeco.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/dragon.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/Duston.png">
    </div>
    <div class="gallery__item">
      <img src="../assets/img/previews/easytryck.png">
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
  &__item{
    width: $gallery__item_width-4-coll;
    height: $gallery__item_height;
    @media  only screen and (max-width: 1440px) {
      width: $gallery__item_width-3-coll;
    }
    @media  only screen and (max-width: 768px) {
      padding-left: 0px;
      width: $gallery__item_width-2-coll;
    }
    img{
      width: 100%;
      height: 100%;
    }
  }
}

</style>
