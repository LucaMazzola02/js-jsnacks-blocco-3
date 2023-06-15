<script>
import AppHeader from './components/HeaderApp.vue';

  export default {
    name: 'App',
    components:{
      AppHeader
    }
}

</script>

<template>
  <AppHeader />
  <GeneralVariable/>
</template>

<style lang="scss">
 @import './styles/general.scss';
</style>
