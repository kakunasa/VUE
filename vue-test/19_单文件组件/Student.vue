<template>
    <div>
        <h2>studentname:{{studentName}}</h2>
        <h2>age:{{age}}</h2>
        <button @click="showName">click and show student name</button>
    </div>
</template>

<script>
    const student = Vue.extend({
        name:'student',
        data() {
            return {
                studentName: "gwckn",
                age: "24",
            }
        },
        methods: {
            showName() {
                alert(this.studentName)
            }
        },
    })
    export default student
</script>