<template>
  <div class="text-center ">
    <h1 class="text-primary"> ciao a tutti 

    </h1>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
 components:{
  AppHeader,
  AppMain,
  AppFooter,
 }
}
</script>

<style lang="scss">
@use './styles/general'
</style>
