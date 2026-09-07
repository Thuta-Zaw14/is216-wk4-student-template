<script setup>
    import { ref } from 'vue'

    // Add code here
    const me = ref('/assets/me.png')
    const width = ref('200')
    const height = ref('200')

</script>

<template>

    <!-- Add code here -->
     <img v-bind:src="me" :width="width" :height="height">
   
</template>
