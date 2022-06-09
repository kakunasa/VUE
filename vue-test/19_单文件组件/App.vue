<template>
<div>
    <School></School>
    <Student></Student>
</div>  
</template>

<script>
import school from './School.vue'
import student from './Student.vue'

export default {
name:'App',
components:{
    School:school,
    Student:student
}
}
</script>