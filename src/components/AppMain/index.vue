<template>
    <div class="main">
        <light v-show="$route.path !== '/home'"></light>
        <router-view></router-view>
    </div>
</template>

<script>
    import Light from './light.vue'
    export default {
        components: {
            Light
        }
    }
</script>