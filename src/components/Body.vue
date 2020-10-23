<template>
    <div>
        <h2>{{ title }}</h2>
        <p>{{ text }}</p>
    </div>
</template>

<script>
export default {
    data(){
        return {
            title: "Body",
            text: "Have a good day!"
        }
    }
}
</script>

<style scoped>
div {
    color: white;
    border-radius: 10px;
    background: #f36353;
    box-shadow:  9px 9px 18px #cc5346, 
                -9px -9px 18px #ff7360;
}
</style>