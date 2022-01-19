<template>
  <div id="app">
    <Header :links="linksArrayNav"/>
    <Main />
    <ServiceSolution />
    <MoveWhitEase />
    <Testimonials />
    <FreeQuote />
    <Footer >
      <AvadaLinks :links="avadaMovers" />
      <PostLink :links="recentPost" />
    </Footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import ServiceSolution from "./components/ServiceSolution.vue";
import MoveWhitEase from "./components/MoveWithEase.vue";
import Testimonials from "./components/Testimonials.vue";
import FreeQuote from "./components/FreeQuote.vue";
import Footer from "./components/Footer.vue";
import AvadaLinks from "./components/AvadaLinks.vue";
import PostLink from "./components/PostLink.vue";


export default {
  name: "App",
  components: {
    Header,
    Main,
    ServiceSolution,
    MoveWhitEase,
    Testimonials,
    FreeQuote,
    Footer,
    AvadaLinks,
    PostLink,
  },
  data: function() {
    return {
        linksArrayNav: [
            {
                text: 'Home',
                url: '#',
                current: true
            },
            {
                text: 'Rates',
                url: '#',
                current: false
            },
            {
                text: 'Testimonials',
                url: '#',
                current: false
            },
            {
                text: 'FAQ',
                url: '#',
                current: false
            },
            {
                text: 'Blog',
                url: '#',
                current: false
            },
            {
                text: 'Contact',
                url: '#',
                current: false
            },
        ],
        avadaMovers: [
            {
                text: 'Home',
                url: '#',
                current: true
            },
            {
                text: 'Rates',
                url: '#',
                current: false
            },
            {
                text: 'Testimonials',
                url: '#',
                current: false
            },
            {
                text: 'Blog',
                url: '#',
                current: false
            },
            {
                text: 'Free Quote',
                url: '#',
                current: false
            },
        ],
        recentPost: [
            {
                text: 'Heading Out To College?',
                url: '#',
                current: true
            },
            {
                text: 'Moving Your Business?',
                url: '#',
                current: false
            },
            {
                text: 'Oustanding Quality',
                url: '#',
                current: false
            },
            {
                text: 'Cost Of Moving',
                url: '#',
                current: false
            },
            {
                text: 'Best Moving Tips',
                url: '#',
                current: false
            },
        ],
    };
  },
};
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: sans-serif;
  background-color: white;
}
</style>
