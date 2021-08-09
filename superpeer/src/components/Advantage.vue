<template>
  <section class="a">
      <h1 class="a__title">What can Superpeer do for you?</h1>
      <p class="a__text">Turn your audience into loyal, paying followers with our seamless video experience and subscriber management tools.</p>
    <div class="a-details">
        <div class="a-card">
            <img src="../img/a1.png" alt="" class="a-card__img">
            <h3 class="a-card__title">Engage with your audience</h3>
            <p class="a-card__text">Connect with your subscribers through interactive livestreams, 1:1s, and our newest feature, Series.</p>
        </div>
        <div class="a-card">
            <img src="../img/a2.png" alt="" class="a-card__img">
            <h3 class="a-card__title">Manage easier</h3>
            <p class="a-card__text">We take care of scheduling, payments, and protecting your privacy, so that you don’t have to.</p>
        </div>
        <div class="a-card">
            <img src="../img/a3.png" alt="" class="a-card__img">
            <h3 class="a-card__title">Earn, your way</h3>
            <p class="a-card__text">Set your own rates and earn revenue through weekly livestreams, channel subscriptions, and even donations.</p>
        </div>
    </div>
    <button class="a__btn v-btn v-btn_s">ALL FEATURES</button>
  </section>
</template>

<script>
export default {
    name: 'Advantage'
}
</script>

<style lang="scss">
    .a{
        display: flex;
        align-items: center;
        flex-direction: column;
        margin-top: 650px;
        &__btn{
            margin-top: 125px;
        }
        &__title{
            font-weight: bold;
            font-size: 48px;
            line-height: 53px;
            text-align: center;
            letter-spacing: 1px;
            color: #222222;
        }
        &__text{
            font-size: 18px;
            max-width: 588px;
            line-height: 25px;
            text-align: center;
            color: #222222;
            margin-top: 24px;
        }
        &-details{
            margin-top: 100px;
            display: flex;
            gap: 30px;
            align-items: center;
            justify-content: space-between;
        }
        &-card{
            &__title{
                margin-top: 60px;
                font-size: 22px;
                line-height: 29px;
                text-align: center;
                color: #222222;
            }
            &__text{
                font-size: 16px;
                line-height: 22px;
                text-align: center;
                color: #555555;
                margin-top: 12px;
                max-width: 277px;
            }
        }
    }
    @media (max-width: 768px) {
        .a{

            &-details{
                flex-wrap: wrap;
                justify-content: center;
            }
        }
    }
    @media (max-width: 675px) {
        .a{
            margin-top: 100px;
        }
    }
    @media (max-width: 584px) {
        .a{
            &__title{
                font-size: 38px;
                line-height: 43px;
            }
            &__text{
                font-size: 14px;
                line-height: 18px;
            }
            &__btn{
                margin-top: 60px;
            }
        }
    }
</style>