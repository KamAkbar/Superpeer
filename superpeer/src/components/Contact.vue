<template>
  <section class="contact">
    <h1 class="contact__title">Featured Superpeer Series
      <img src="../img/contactvector.png" alt="" class="contact__vector">
    </h1>
    <div class="contact-info">
      <div class="contact-img">
       <img src="../img/contact.png" alt="" class="contact__img">
      </div>
      <div class="contact-form form">
        <img src="../img/contactask.png" alt="" class="form__avatar">
        <svg class="form__icon" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M10.4065 9.21599C10.2709 9.15058 10.1215 9.11904 9.97097 9.12405C9.82049 9.12907 9.67347 9.1705 9.54252 9.24479C9.41589 9.31564 9.31018 9.41861 9.23602 9.54333C9.16187 9.66804 9.12189 9.8101 9.12012 9.95519V14.0352C9.12012 14.3328 9.28332 14.6112 9.54252 14.7552C9.81132 14.9088 10.1281 14.9184 10.4065 14.7936L14.2369 12.9792C14.4278 12.8951 14.5902 12.7573 14.7041 12.5826C14.8181 12.4079 14.8788 12.2038 14.8788 11.9952C14.8788 11.7866 14.8181 11.5825 14.7041 11.4078C14.5902 11.2331 14.4278 11.0953 14.2369 11.0112L10.4065 9.21599Z" stroke="black" stroke-width="0.06" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M18.4511 3.35986H5.54873C5.13518 3.35986 4.79993 3.69511 4.79993 4.10866V19.8911C4.79993 20.3046 5.13518 20.6399 5.54873 20.6399H18.4511C18.8647 20.6399 19.1999 20.3046 19.1999 19.8911V4.10866C19.1999 3.69511 18.8647 3.35986 18.4511 3.35986Z" stroke="black" stroke-width="0.06" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M21.6673 5.52002C21.9695 5.52506 22.2576 5.64865 22.4695 5.86415C22.6814 6.07964 22.8001 6.36979 22.8001 6.67202V17.328C22.8001 17.6302 22.6814 17.9204 22.4695 18.1359C22.2576 18.3514 21.9695 18.475 21.6673 18.48M2.33287 5.52002C2.03068 5.52506 1.74258 5.64865 1.53067 5.86415C1.31876 6.07964 1.20003 6.36979 1.20007 6.67202V17.328C1.20003 17.6302 1.31876 17.9204 1.53067 18.1359C1.74258 18.3514 2.03068 18.475 2.33287 18.48V5.52002Z" stroke="black" stroke-width="0.06" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
        <h1 class="form__title">Q&A with a Professional Photographer</h1>
        <p class="form__text">Being a photographer isn't just a job. Let's delve into real examples of how photography has changed lives and shaped the world. Whether you've been creating photos for years or weeks, we all have some similar feelings when we get behind a lens.</p>
        <div class="form-status">
          <div>
            <h5 class="form__status">taught by</h5>
            <h4 class="form__name">Adam Katz Sinding</h4>
          </div>
          <div>
            <h5 class="form__status">starts</h5>
            <h4 class="form__name">October 2021</h4>
          </div>
        </div>
        <button class="form__btn v-btn v-btn_s">NOTIFY ME</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'Contact'
}
</script>

<style lang="scss">
  .contact{
    margin-top: 200px;
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    &__title{
      display: flex;
      flex-direction: column;
      align-items: center;
      font-weight: bold;
      font-size: 48px;
      line-height: 53px;
      text-align: center;
      letter-spacing: 1px;
      color: #222222;
    }
    &__vector{
      max-width: 592px;
      margin-top: 5px;
    }
    &-info{
      margin-top: 40px;
    }
    &-img{
      max-width: 834px;
    }
    &__img{
      width: 100%;
    }
  }
  .form{
    background: #FFFFFF;
    border-radius: 24px;
    position: absolute;
    left: 48%;
    bottom: -750px;
    transform: translate(-50%, -50%);
    padding: 30px 40px;
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 674px;
    &__btn{
      margin-top: 56px;
    }
    &__title{
      font-size: 22px;
      line-height: 29px;
      text-align: center;
      color: #222222;
      margin-top: 4px;
    }
    &__icon{
      margin-top: 24px;
    }
    &__text{
      font-size: 16px;
      line-height: 22px;
      text-align: center;
      color: #555555;
      margin-top: 33px;
    }
    &-status{
      margin-top: 23px;
      display: flex;
      flex-direction: row;
      gap: 80px;
    }
    &__status{
      font-size: 12px;
      line-height: 17px;
      text-align: center;
      color: #98A3B6;
    }
    &__name{
      font-size: 16px;
      line-height: 22px;
      text-align: center;
      color: #000000;
    }

  }
  @media (max-width: 768px) {
    .form{
      min-width: 520px;
    }
  }
  @media (max-width: 683px) {
    .contact{
      display: none ;
    }
  }
</style>