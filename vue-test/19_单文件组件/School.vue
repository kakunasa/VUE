<template>
    <div class="demo">
        <h2>schoolname:{{schoolName}}</h2>
        <h2>schooladdress{{address}}</h2>
        <button @click="showName">click and show school name</button>
    </div>
</template>

<script>
    const school = Vue.extend({
        name:'school',
        data() {
            return {
                schoolName: "sophia",
                address: "tokyo",
            }
        },
        methods: {
            showName() {
                alert(this.schoolName)
            }
        },
    })
    export default school
</script>

<style>
    .demo {
        background-color: orange;
    }
</style>