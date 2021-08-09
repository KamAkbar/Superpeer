<template>
  <section class="series">
      <div class="series-details">
          <h1 class="series__title">Introducing Superpeer Series</h1>
          <p class="series__text">With series, you can create and sell any combination of on-demand video and live stream content. With cohort-based classes you can interact with your audience in a more engaging way.</p>
      </div>
        <div class="series-img">
            <img src="../img/series.png" alt="" class="series__img">
        </div>
    <div class="s-details">
        <div class="s-card">
            <img src="../img/s1.png" alt="" class="s__img">
            <h3 class="s__title">Customize the content</h3>
            <p class="s__text">Organize your live streams, pre-recorded videos, and hosted events into purchasable content packages for your audience.</p>
        </div>
        <div class="s-card">
            <img src="../img/s2.png" alt="" class="s__img">
            <h3 class="s__title">Set the pace</h3>
            <p class="s__text">Series can be cohort-based for engaging group discussions or even on-demand for the self-paced learner.</p>
        </div>
        <div class="s-card">
            <img src="../img/s3.png" alt="" class="s__img">
            <h3 class="s__title">Immerse the audience</h3>
            <p class="s__text">Participants can chat with each other, send private messages, and raise a hand to be brought up on the stage during live events.</p>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'Series'
}
</script>

<style lang="scss">
    .series{
        padding-top: 120px;
        position: relative;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-top: 140px;
        background: linear-gradient(180deg, #E4DDFF 0%, rgba(255, 255, 255, 0) 100%);
        &-details{
            display: flex;
            flex-direction: column;
            gap: 14px;
            align-items: center;
        }
        &__title{
            font-size: 64px;
            line-height: 70px;
            text-align: center;
            letter-spacing: 1px;
            color: #222222;
            max-width: 931px;
        }
        &__text{
            font-size: 22px;
            line-height: 29px;
            text-align: center;
            color: #555555;
            max-width: 714px;
        }
        &-img{
            max-width: 850px;
            margin-top: 88px;
        }
        &__img{
            width: 100%;
        }
    }
    .s{
        &-card{
            display: flex;
            flex-direction: column;
            align-items: center;
        }
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
    @media (max-width: 768px) {
        .series{
            margin-top: 80px;
            &__title{
            font-size: 44px;
            line-height: 50px;
            }
            &__text{
                font-size: 16px;
                line-height: 23px;
            }
            &-img{
                margin-top: 40px;
            }
            &__bg{
                top: 100px;
            }
        }
    }
    .s{
        &-details{
            margin-top: 100px;
            display: flex;
            gap: 30px;
            align-items: center;
            flex-wrap: wrap;
            justify-content: space-between;
        }
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
        @media (max-width: 768px) {
            .s{
                &-details{
                    justify-content: center!important;
                }
            }
            }
    }
    @media (max-width: 675px) {
    .s{
        margin-top: 100px;
    }
}
    @media (max-width: 584px) {
        .s{
            &-details{
                justify-content: center!important;
            }
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