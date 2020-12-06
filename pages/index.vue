<template>
  <div class="container">
    <Nav />
    <Header />
    <About />
    <Services />
    <Contact />
  </div>
</template>

<script>
  import Nav from '~/components/nav'
  import Header from '~/components/header'
  import Services from '~/components/services'
  import About from '~/components/about'
  import Contact from '~/components/contacts'
 

export default {
  components:{
    Nav, Header, Services, About, Contact
  }
}
</script>

<style scoped>
.container{
  background-image: url('../static/trait.png');
  background-size: cover;
  background-attachment: fixed;
  height: 100%;
  position: relative;
  z-index: -1;
}
</style>
