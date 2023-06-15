<script>
    export default {
    name: 'AppHeader',
    data(){
        return{
            links : [
                'Home',
                'Contacts',
                'Listin',
                'Instagram',
            ]
        }
    }
    
};
</script>

<template>
    <div class="nav-bar">
        <ul>
            <li v-for="link in links">
                {{ link }}
            </li>
        </ul>
    </div>
  
</template>

<style lang="scss">


</style>
