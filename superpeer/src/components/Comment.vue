<template>
  <section class="comment">
      <h1 class="comment__title">Don’t just take our word for it <svg class="comment__icon" width="135" height="104" viewBox="0 0 135 104" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M6.07002 53.16L39.57 0H64.42L43.04 44.78C48.24 46.7 52.67 50.27 56.34 55.47C59.9793 60.6184 61.8974 66.7857 61.82 73.09C61.82 81.56 58.74 88.89 52.58 95.04C49.7708 97.9363 46.3975 100.226 42.6686 101.767C38.9397 103.308 34.9343 104.068 30.9 104C22.43 104 15.1 101.02 8.95002 95.04C6.06906 92.1656 3.79288 88.7435 2.25573 84.9753C0.718585 81.2072 -0.0483978 77.1693 2.13226e-05 73.1C2.13226e-05 66.17 2.02002 59.52 6.07002 53.17V53.16ZM75.97 53.16L109.5 0H134.34L112.97 44.78C118.17 46.7 122.6 50.27 126.25 55.47C129.897 60.6157 131.822 66.7834 131.75 73.09C131.75 81.56 128.66 88.89 122.5 95.04C119.692 97.935 116.32 100.224 112.593 101.765C108.866 103.306 104.863 104.067 100.83 104C92.36 104 85.04 101.02 78.88 95.04C75.9936 92.1682 73.7119 88.7471 72.1696 84.9788C70.6272 81.2105 69.8555 77.1714 69.9 73.1C69.9 66.17 71.92 59.52 75.97 53.17V53.16Z" fill="#FFF7E0"/>
        </svg></h1>
    <VueSlickCarousel :arrows="true" :dots="true">
      <div>
          <p class="comment__context">"I have gotten at least 50 times the value from Superpeer. I use Superpeer often. I could probably go into sales for you."</p>
          <div class="comment-details">
              <img src="https://picsum.photos/64" alt="" class="comment__img">
              <h5 class="comment__name">Janine Sickmeyer</h5>
              <p class="comment__job">Tech entrepreneur & Angel investor</p>
          </div>
      </div>
      <div>
          <p class="comment__context">"Not able to tell you how happy I am with Superpeer. It's incredible. Your company is truly upstanding and is behind its product 100%."</p>
          <div class="comment-details">
              <img src="https://picsum.photos/64" alt="" class="comment__img">
              <h5 class="comment__name">Joshbek Toshovich</h5>
              <p class="comment__job">Sciantice & Billionere</p>
          </div>
      </div>
      <div>
          <p class="comment__context">"We've used Superpeer for the last five years. Just what I was looking for. It's exactly what I've been looking for. After using Superpeer my business skyrocketed!"</p>
          <div class="comment-details">
              <img src="https://picsum.photos/64" alt="" class="comment__img">
              <h5 class="comment__name">Anastasiya Khan</h5>
              <p class="comment__job">Programmist & Public Figurue</p>
          </div>
      </div>
      <div>
          <p class="comment__context">"Since I invested in Superpeer I made over 100,000 dollars profits. Superpeer is awesome! We've seen amazing results already."</p>
          <div class="comment-details">
              <img src="https://picsum.photos/64" alt="" class="comment__img">
              <h5 class="comment__name">Akhim Li</h5>
              <p class="comment__job">Business Leader & Public Speaker</p>
          </div>
      </div>
    </VueSlickCarousel>
  </section>
</template>

<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

export default {
    name: 'Comment',
    components: { VueSlickCarousel }
}
</script>

<style lang="scss">
    .comment{
        margin-top: 260px;
        display: flex;
        flex-direction: column;
        align-items: center;
        background: linear-gradient(180deg, #FFFAEC 0%, rgba(255, 255, 255, 0) 100%);
        &__title{
            position: relative;
            padding-top: 100px;
            font-size: 48px;
            line-height: 53px;
            text-align: center;
            letter-spacing: 1px;
            color: #222222;
        }
        &__icon{
            position: absolute;
            left: 260px;
            top: 70px;
            z-index: -1;
        }
        &__context{
            margin-top: 60px;
            font-size: 32px;
            line-height: 40px;
            text-align: center;
            color: #222222;
        }
        &-details{
            margin-top: 60px;
            display: flex;
            align-items: center;
            flex-direction: column;
        }
        &__img{
            border: 3px solid #FAC734;
            box-sizing: border-box;
            filter: drop-shadow(0px 0px 0px #FFD75B);
            border-radius: 32px;
        }
        &__name{
            font-size: 16px;
            line-height: 22px;
            text-align: center;
            color: #222222;
            margin-top: 16px;
        }
        &__job{
            font-size: 12px;
            line-height: 17px;
            text-align: center;
            color: #222222;
            margin-top: 2px;
        }
    }
    .slick-slider{
        max-width: 70%;
    }
    @media (max-width: 425px) {
        .comment{
            margin-top: 60px;
            &__icon{
                display: none;
            }
            &__title{
                font-size: 38px;
                line-height: 43px;
            }
            &__context{
                font-size: 22px;
                line-height: 30px;
            }
        }
    }
</style>