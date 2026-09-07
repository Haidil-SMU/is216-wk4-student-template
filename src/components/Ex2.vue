<script setup>
    import { ref } from 'vue'

    // Add code here
    const image  = {
        src: '/assets/me.png',
        width: '200',
        height: '200px'
    }

    const obj = {
        width: '200',
        height: '200',
        src: '/assets/me.png'
    }

</script>

<template>

    <!-- Add code here -->
     <img v-bind:src="myImg" width="width" height="height" />

     <img v-bind="obj"/>
   
</template>
