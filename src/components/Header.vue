<template>
    <div>
        <h1>{{ title }}</h1>
        <p>{{ text }}</p>
    </div>
</template>

<script>
export default {
    data(){
        return {
            title: "Header",
            text: "Hello Vue.js!"
        }
    }
}
</script>

<style scoped>
div {
    border-radius: 10px;
    background: #f36353;
    box-shadow:  9px 9px 18px #cc5346, 
                -9px -9px 18px #ff7360;
}
</style>