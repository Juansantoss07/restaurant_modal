<script>
    import Header from "./components/Header/Header.vue"
    import Logo from "./components/Logo/Logo.vue"
    import Footer from "./components/Footer/Footer.vue"

    export default{
        components:{
            Header,
            Logo,
            Footer
        }
    }
</script>

<template>
    <section>
          <Header />
          <Logo />
          <Footer />
    </section>
  
    
</template>

<style lang="scss" src="./style.scss"/>
