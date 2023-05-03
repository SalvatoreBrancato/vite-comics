<script>
import AppNav from "./components/Nav.vue"
import AppMain from "./components/Main.vue"
import AppFooter from "./components/Footer.vue";


export default{
    name: "App",
    components: {
        AppNav,
        AppMain,
        AppFooter
    }
}
</script>

<template>
  <div>
   <AppNav/>
   <AppMain/>
   <AppFooter/>
  </div>
</template>

<style lang="scss">
@use "./style/main.scss" as *;
</style>
