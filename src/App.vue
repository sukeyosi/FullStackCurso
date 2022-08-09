<template>
  <div id="nav">
    <home-menu />
    <hr />
  </div>
  <router-view />
</template>
<script>
import HomeMenu from "./components/home-menu.vue";
export default {
  components: {
    HomeMenu,
  },
};
</script>


    HomeMenucript>
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  hr {
    border-bottom: 1.4px  #080303;
  }
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
