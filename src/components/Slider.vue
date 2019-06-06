<template>
  <md-card>
    <md-card-actions>
      <div class="md-subhead">
        <span>Loop Mode / Infinite Loop</span>
        <span>（</span>
        <span>无限循环模式</span>
        <span>）</span>
      </div>
      <md-button class="md-icon-button"
                 target="_blank"
                 href="https://github.com/surmon-china/vue-awesome-swiper/blob/master/examples/20-infinite-loop.vue">
        <md-icon>code</md-icon>
      </md-button>
    </md-card-actions>
    <md-card-media>
      <!-- swiper -->
      <swiper :options="swiperOption" class="swiper">
        <swiper-slide class="sw"><img src="../img/c1.jpg"></swiper-slide>
        <swiper-slide class="sw"><img src="../img/c2.jpg"></swiper-slide>
        <swiper-slide class="sw"><img src="../img/c3.jpg"></swiper-slide>
        <swiper-slide class="sw"><img src="../img/c4.jpg"></swiper-slide>
        <swiper-slide class="sw"><img src="../img/c5.jpg"></swiper-slide>
        <swiper-slide class="sw"><img src="../img/c6.jpg"></swiper-slide>
        <swiper-slide class="sw"><img src="../img/c7.jpg"></swiper-slide>
        <swiper-slide class="sw"><img src="../img/c8.jpg"></swiper-slide>
        <swiper-slide class="sw"><img src="../img/bg2.jpg"></swiper-slide>
        <swiper-slide class="sw"><img src="../img/bg1.jpg"></swiper-slide>
        <div class="swiper-pagination" slot="pagination"></div>
        <div class="swiper-button-prev" slot="button-prev"></div>
        <div class="swiper-button-next" slot="button-next"></div>
      </swiper>
    </md-card-media>
  </md-card>
</template>

<script>
  export default {
    data() {
      return {
        swiperOption: {
          slidesPerView: 1,
          spaceBetween: 30,
          loop: true,
          pagination: {
            el: '.swiper-pagination',
            clickable: true
          },
          navigation: {
            nextEl: '.swiper-button-next',
            prevEl: '.swiper-button-prev'
          }
        }
      }
    }
  }
</script>

<script>

import 'swiper/dist/css/swiper.css'

import { swiper, swiperSlide } from 'vue-awesome-swiper'

export default {
  components: {
    swiper,
    swiperSlide
  }
}
</script>

<style type="text/css">
  .sw img{
    width:90%; 
    border: 20px solid #ff443c;
  }
 .swiper{background: url("../img/bg3.png");} 
 .md-subhead {font-family:'Outrunfuture';}
</style>
