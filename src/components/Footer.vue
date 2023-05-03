<script>
import AppFooter_s from "./Footer_s.vue"
import AppFooter_c from "./Footer_c.vue"
import AppFooter_e from "./Footer_e.vue"

export default{
        name: "AppFooter",
        components: {
          AppFooter_s,
          AppFooter_c,
          AppFooter_e
        }
}
</script>

<template>
  <AppFooter_s/>
  <AppFooter_c/>
  <AppFooter_e/>
</template>

<style lang="scss" scoped>


</style>