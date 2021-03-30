<template>
  <div class="nav-bar">
    <div class="nav-bar__logo">
      <img src="@/assets/img/logo.svg" alt="">
    </div>
    <nav class="nav-bar__nav">
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
    <div class="nav-bar__social-links">
      <div class="nav-bar__social-links_line">
        <a href="/instagram">
          <svg class="social-link" viewBox="0 0 333 337">
            <g>
              <path class="social-link__icon" d="M30 169c0,-45 0,-50 1,-67 0,-16 3,-25 5,-31 3,
              -8 7,-13 13,-19 6,-6 11,-9 19,-12 6,-2 14,-5 30,-6 18,-1 23,-1 67,
              -1 44,0 50,0 67,1 16,1 25,4 31,6 7,3 13,6 19,12 5,6 9,11 12,19 2,6 5,
              15 6,31 0,17 1,22 1,67 0,44 -1,49 -1,66 -1,16 -4,25 -6,31 -3,8 -7,
              13 -12,19 -6,6 -12,9 -19,12 -6,3 -15,5 -31,6 -17,1 -23,1 -67,1 -44,
              0 -49,0 -67,-1 -16,-1 -24,-3 -30,-6 -8,-3 -13,-6 -19,-12 -6,-6 -10,
              -11 -13,-19 -2,-6 -5,-15 -5,-31 -1,-17 -1,-22 -1,-66zm135 -85c-47,
              0 -85,38 -85,85 0,46 38,84 85,84 47,0 85,-38 85,-84 0,-47 -38,-85 -85,
              -85zm-55 85c0,-31 25,-55 55,-55 31,0 55,24 55,55 0,30 -24,55 -55,55 -30,
              0 -55,-25 -55,-55zm124 -89c0,11 8,20 19,20 11,0 20,-9 20,-20 0,-11 -9,
              -19 -20,-19 -11,0 -19,8 -19,19zm95 20c0,-17 -3,-29 -7,-40 -5,-10 -10,
              -20 -19,-29 -10,-9 -19,-15 -30,-19 -10,-4 -22,-7 -40,-8 -17,0 -23,-1 -68,
              -1 -45,0 -50,1 -68,1 -17,1 -30,4 -40,8 -11,4 -20,10 -29,19 -9,9 -15,
              19 -19,29 -4,11 -7,23 -8,40 -1,18 -1,24 -1,69 0,44 0,50 1,68 1,17 4,29 8
              ,40 4,11 10,20 19,29 9,9 18,15 29,19 10,4 23,7 40,8 18,1 23,1 68,1 45,
              0 51,0 68,-1 18,-1 30,-4 40,-8 11,-4 20,-10 30,-19 9,-9 14,-18 19,-29 4,
              -11 7,-23 7,-40 1,-18 1,-24 1,-68 0,-45 0,-51 -1,-69z"/>
            </g>
          </svg>
        </a>
        <a href="/dribbble">
          <svg class="social-link" viewBox="0 0 358 362">
            <g>
              <path class="social-link__icon" d="M262 307c-3,-14 -12,-60 -29,-108 49,
              -6 93,8 93,8l1 0c-7,42 -31,77 -65,100zm31 -221l1 -1c22,25 35,59 35,
              95l0 0c0,0 -51,-13 -106,-6 -1,-4 -3,-8 -5,-12 -2,-5 -5,-11 -8,-17 61,
              -25 83,-59 83,-59zm-115 247c-36,0 -68,-13 -94,-33 9,-15 43,-61 103,-88 5,
              -3 11,-5 17,-6 20,52 26,91 32,115 -18,8 -38,12 -58,12zm-151 -152c0,-1 0,
              -3 0,-4 13,0 66,2 145,-19 3,-1 6,-1 9,-2 2,4 4,8 6,12 2,4 4,8 6,12 -6,
              2 -11,3 -16,5 -70,28 -107,86 -113,96 -23,-27 -37,-61 -37,-100zm85 -136c8,
              11 31,43 56,86l-4 1c-62,18 -119,17 -134,17 10,-46 41,-84 82,-104zm66 -15c38,
              0 73,14 99,37 -19,23 -41,40 -80,55 -22,-40 -46,-76 -55,-88 12,-2 24,-4 36,
              -4zm-1 -26c-97,0 -177,79 -177,177 0,98 80,177 177,177 98,0 177,-79 177,
              -177 0,-98 -79,-177 -177,-177z"/>
            </g>
          </svg>
        </a>
      </div>
      <div class="nav-bar__social-links_line">
        <a href="/behance">
          <svg class="social-link" viewBox="0 0 387 246">
            <g>
              <path class="social-link__icon" d="M124 195l-72 0 0 -61 68 0c20,0 27,17 27,29 0,
              11 -1,32 -23,32zm127 -155l97 0 0 -24 -97 0 0 24zm49 58c38,0 37,36 37,
              36l-74 0c0,0 -1,-36 37,-36zm3 108c-43,0 -40,-42 -40,-42l123 0c0,-77 -39,
              -103 -86,-103 -47,0 -86,40 -86,88 0,48 22,95 90,95 67,0 82,-59 82,
              -59l-45 0c0,0 -4,21 -38,21zm-251 -163l58 0c23,0 27,17 27,24 0,6 -2,
              28 -22,28l-63 0 0 -52zm102 66c17,-8 34,-14 34,-52 0,-38 -31,-54 -54,
              -54l-133 0 0 235 116 0c60,0 81,-30 81,-71 0,-42 -27,-58 -44,-58z"/>
            </g>
          </svg>
        </a>
        <a href="/linkedin">
          <svg class="social-link" viewBox="0 0 287 279">
            <g>
              <path class="social-link__icon" d="M285 275l-59 0 0 -107c0,-8 -1,-12 -6,
              -20 -4,-8 -12,-14 -25,-14 -10,0 -19,5 -26,13 -4,4 -5,8 -7,
              12l0 116 -61 0 0 -183 61 0 0 29c6,-9 16,-33 57,-33 45,0 66,37 66,
              80l0 107zm-248 -207c-19,0 -34,-15 -34,-32 0,-18 15,-32 34,-32 18,
              0 33,14 33,32 0,17 -15,32 -33,32zm31 207l-63 0 0 -183 63 0 0 183z"/>
            </g>
          </svg>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Gallery',
};
</script>

<style lang="scss" scoped>
svg.social-link {
  height: 30px;
  width: 30px;
}
.social-link__icon {
  fill: #454545;
  fill-rule:nonzero;
  transition: all 1s ease-out;
}
.social-link__icon:hover {
  fill: #fff;
}
.nav-bar{
  background-color: #000;
  width: 225px;
  height: 100%;
  position: fixed;
  padding-top: 75px;
  display: flex;
  flex-direction: column;
  align-items: center;
  @media  only screen and (max-width: 768px) {
    display: none;
  }
  &__nav{
    padding-top: 50px;
    ul{
      padding: 0;
      list-style: none;
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
  &__social-links{
    width: 100%;
    &_line{
      width: 100%;
      display: flex;
      justify-content: center;
      a{
        margin: 10px;
      }
    }
  }
}
</style>
