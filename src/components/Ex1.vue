<script setup>
    import { ref } from 'vue'

    // Add code here
    // challenge: use array  
    const message = ref("Choose your fav")
    const fruits = ref (["apple","orange","peach"])
    
</script>

<template>
    {{ message }} 
   
    <label for=""> <input type="radio" name="fruit"> {{ fruits[0] }} </label> 
    <label for=""> <input type="radio" name="fruit"> {{ fruits[1] }} </label> 
    <label for=""><input type="radio" name="fruit"> {{ fruit[2] }} </label> 
    
</template>

<style scoped>
</style>
