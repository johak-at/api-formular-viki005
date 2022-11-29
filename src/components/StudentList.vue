<script setup>
import {ref} from 'vue'
onMounted(async () =>{
    const response = await fetch("https://pb.seiwald.club/api/collections/4bhk/records")
})
</script>
<template> 
<h1>OurStudents</h1>
</template>