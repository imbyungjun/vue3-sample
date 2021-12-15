<template>
    <h1>Hello Vue3!</h1>
    <MyComponent msg="Hello Vue3 + TS"/>
</template>
<script lang="ts">
import { defineComponent } from 'vue';
import MyComponent from './components/MyComponent.vue';

export default defineComponent({
    name: 'App',
    components: {
        MyComponent
    }
})
</script>
<style scoped>
h1 {
    color: #acacac
}
</style>
