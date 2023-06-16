<script>

    export default {
    name: 'NavLink',
    props : {
        singleLink : Object
    }   
};
</script>

<template>
    <div class="nav-bar">
        <ul>
            <li v-for="link in links">
                :singleLink = "link";
            </li>
        </ul>
    </div> 
</template>

<style lang="scss">


</style>