<script>

import navLink from './components/Navlink.vue';

    export default {
    name: 'AppHeader',
    components:{
      navLink,
    },
    data(){
        return{
            links : [
                'Home',
                'Contacts',
                'Listin',
                'Profile',
                'Sales',
            ]
        }
    }    
};

</script>

<template>
    <navLink />
</template>

<style lang="scss">


</style>
