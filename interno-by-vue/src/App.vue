<template>
  <div id="app">
    <div class="wrapper">
        <div class="overlay"></div>
<HeaderBlock />
<MainBlock/>
<FooterBlock/>
<ArticlesSort/>
<ArticlesFilter/>
<ProjectsComp/>
    </div>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HeaderBlock from './components/HeaderBlock.vue'
import MainBlock from './components/MainBlock.vue'
import FooterBlock from './components/FooterBlock.vue'
import ArticlesSort from './pages/ArticlesSort.vue'
import ArticlesFilter from './pages/ArticlesFilter.vue'
import ProjectsComp from './components/ProjectsComp.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    HeaderBlock,
    MainBlock,
    FooterBlock,
    ArticlesSort,
    ArticlesFilter,
    ProjectsComp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
