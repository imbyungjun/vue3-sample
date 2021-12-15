<template>
    <h2>{{ message }}</h2>
</template>
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'MyComponent',
    props: ['msg'],
    data() {
        return {
            message: this.msg
        }
    }
})
</script>
<style scoped>
h2 {
    color: #1347a0
}
</style>
