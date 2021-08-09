<template>
  <div id="app">
    <Header />
    <Intro />
    <Card />
    <Contact />
    <Advantage />
    <Comment />
    <Series />
    <Superpeer />
    <Footer /> 
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Intro from './components/Intro.vue'
import Card from './components/Card.vue'
import Contact from './components/Contact.vue'
import Advantage from './components/Advantage.vue'
import Comment from './components/Comment.vue'
import Series from './components/Series.vue'
import Superpeer from './components/Superpeer.vue'
import Footer from './components/Footer.vue'
// import Advantage from './components/Advantage.vue'
// import Offer from './components/Offer.vue'
// import Sponsor from './components/Sponsor.vue'
// import Support from './components/Support.vue'
// import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    Header, Intro, Card, Contact, Advantage, Comment, Series, Superpeer, Footer /* Advantage, Offer, Sponsor, Support, Contact, Footer */
  },
}
</script>

<style lang="scss">

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');
  .v-btn{
  padding: 16px 33px;
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 16px;
  line-height: 22px;
  text-align: center;
  text-transform: uppercase;
  color: #222222;
  border-radius: 8px;
  border: none;
  &_p{
    background: #FFD338;
  }
  &_s{
    background: #FFEDC2;
  }
}
#app {
  font-family: 'Roboto', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  a{
  text-decoration: none;
  color: inherit;
    &:hover{
      color: #FFD338;
      transition: .5s;
  }

}
}
</style>
