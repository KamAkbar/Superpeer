<template>
  <section class="v-card container">
      <div class="v-card-details">
          <h1 class="v-card__title">See what magic our community is creating</h1>
          <p class="v-card__text">Explore these examples of Series, created by our Superpeers, and reserve your spot today</p>
      </div>
      <div class="v-card boards">
          <div class="board">
              <div class="board-img">
                <img src="https://picsum.photos/402/225" alt="v-card Image" class="board__img">
                <img src="https://picsum.photos/70" alt="Author's Picture" class="board__avatar">
              </div>
              <div class="board-info">
                  <h1 class="board__title">{{arr[0].title}}</h1>
                  <h5 class="board__name">{{arr[0].name}}</h5>
                  <p class="board__text">{{arr[0].text}}</p>
              </div>
              <div class="board-details">
                  <h5 class="board__start">Starts</h5>
                  <p class="board__data">{{arr[0].data}}</p>
                  <button class="board__btn v-btn v-btn_s">ENROLL</button>
            </div>
          </div>
          <div class="board">
              <div class="board-img">
                <img src="https://picsum.photos/402/225" alt="v-card Image" class="board__img">
                <img src="https://picsum.photos/70" alt="Author's Picture" class="board__avatar">
              </div>
              <div class="board-info">
                  <h1 class="board__title">{{arr[0].title}}</h1>
                  <h5 class="board__name">{{arr[0].name}}</h5>
                  <p class="board__text">{{arr[0].text}}</p>
              </div>
              <div class="board-details">
                  <h5 class="board__start">Starts</h5>
                  <p class="board__data">{{arr[0].data}}</p>
                  <button class="board__btn v-btn v-btn_s">ENROLL</button>
            </div>
          </div>
          <div class="board">
              <div class="board-img">
                <img src="https://picsum.photos/402/225" alt="v-card Image" class="board__img">
                <img src="https://picsum.photos/70" alt="Author's Picture" class="board__avatar">
              </div>
              <div class="board-info">
                  <h1 class="board__title">{{arr[0].title}}</h1>
                  <h5 class="board__name">{{arr[0].name}}</h5>
                  <p class="board__text">{{arr[0].text}}</p>
              </div>
              <div class="board-details">
                  <h5 class="board__start">Starts</h5>
                  <p class="board__data">{{arr[0].data}}</p>
                  <button class="board__btn v-btn v-btn_s">ENROLL</button>
            </div>
          </div>
          <div class="board">
              <div class="board-img">
                <img src="https://picsum.photos/402/225" alt="v-card Image" class="board__img">
                <img src="https://picsum.photos/70" alt="Author's Picture" class="board__avatar">
              </div>
              <div class="board-info">
                  <h1 class="board__title">{{arr[0].title}}</h1>
                  <h5 class="board__name">{{arr[0].name}}</h5>
                  <p class="board__text">{{arr[0].text}}</p>
              </div>
              <div class="board-details">
                  <h5 class="board__start">Starts</h5>
                  <p class="board__data">{{arr[0].data}}</p>
                  <button class="board__btn v-btn v-btn_s">ENROLL</button>
            </div>
          </div>
          <div class="board">
              <div class="board-img">
                <img src="https://picsum.photos/402/225" alt="v-card Image" class="board__img">
                <img src="https://picsum.photos/70" alt="Author's Picture" class="board__avatar">
              </div>
              <div class="board-info">
                  <h1 class="board__title">{{arr[0].title}}</h1>
                  <h5 class="board__name">{{arr[0].name}}</h5>
                  <p class="board__text">{{arr[0].text}}</p>
              </div>
              <div class="board-details">
                  <h5 class="board__start">Starts</h5>
                  <p class="board__data">{{arr[0].data}}</p>
                  <button class="board__btn v-btn v-btn_s">ENROLL</button>
            </div>
          </div>
          <div class="board">
              <div class="board-img">
                <img src="https://picsum.photos/402/225" alt="v-card Image" class="board__img">
                <img src="https://picsum.photos/70" alt="Author's Picture" class="board__avatar">
              </div>
              <div class="board-info">
                  <h1 class="board__title">{{arr[0].title}}</h1>
                  <h5 class="board__name">{{arr[0].name}}</h5>
                  <p class="board__text">{{arr[0].text}}</p>
              </div>
              <div class="board-details">
                  <h5 class="board__start">Starts</h5>
                  <p class="board__data">{{arr[0].data}}</p>
                  <button class="board__btn v-btn v-btn_s">ENROLL</button>
            </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'v-Card',
      data() {
        return {
        arr: [
            {
            title: 'Masterclass on Fundraising Strategies',
            name: 'Dawn Dickson',
            text: 'Entry-level strategies from an expert in entrepreneurship, business development and fundraising. The first female founder to raise $1M> in an equity crowdfunding campaign will teach you the best in investment, crowdfunding and overall fundraising strategies to capitalize your business at every level.',
            data: 'September 9, 2021',
            }
            ],
            }
        },
}
</script>

<style lang="scss">
    .v-card{
        margin-top: 200px;
        &-details{
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 11px;
        }
        &__title{
            font-weight: bold;
            font-size: 48px;
            line-height: 53px;
            text-align: center;
            letter-spacing: 1px;
            color: #222222;
            max-width: 540px;
        }
        &__text{
            max-width: 507px;
            font-size: 18px;
            line-height: 25px;
            text-align: center;
            color: #222222;
        }
    }
    .boards{
    max-width: 402px;
    margin-top: 60px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 127px;
    }
    .board{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 0;
        &-img{
            position: relative;
            max-width: 402px;
        }
        &__img{
            object-fit: contain;
        }
        &__avatar{
            position: absolute;
            bottom: -30%;
            left: 50%;
            transform: translate(-50%, -50%);
            border-radius: 50%;
            padding: 8px;
            background-color: #fff;
            object-fit: contain;
        }
        &-info{
            margin-top: 48px;
            
        }
        &__title{
            font-weight: bold;
            font-size: 22px;
            line-height: 29px;
            text-align: center;
            color: #222222;
        }
        &__name{
            font-size: 16px;
            margin-top: 11px;
            line-height: 22px;
            text-align: center;
            color: #555555;
        }
        &__text{
            font-size: 16px;
            line-height: 22px;
            text-align: center;
            color: #555555;
            margin-top: 16px;
        }
        &-details{
            display: flex;
            align-items: baseline;
            gap: 24px;
        }
        &__start{
            font-size: 16px;
            line-height: 22px;
            text-align: center;
            color: #98A3B6;
        }
        &__data{
            font-size: 16px;
            line-height: 22px;
            text-align: center;
            color: #000000;
        }
    }
    @media (max-width: 992px) {
        .board{
            &__img{
                width: 304px;
            }
            &__avatar{
                width: 60px;
                padding: 5px;
            }
        }
    }
    @media (max-width: 992px) {
            .boards{
                grid-template-columns: 1fr;
            }
    }
    @media (max-width: 425px) {
        .v-card{
            &__title{
                font-size: 38px;
                line-height: 43px;
            }
            &__text{
                font-size: 16px;
                line-height: 20px;
            }
        }
        .board{
            &__title{
                font-size: 20px;
                line-height: 25px;
            }
            &__data{
                font-size: 12px;
                line-height: 14px;
            }
            &__btn{
                padding: 8px 10px!important;
                font-size: 14px!important;
            }
        }
    }
</style>