<template>
    <div class="m-5 p-5">
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
    text-align: center;
    color: white;
    border-radius: 10px;
    background: #f36353;
    box-shadow:  5px 5px 5px #cc5346, 
                -5px -5px 5px #ff7360;
}
</style>