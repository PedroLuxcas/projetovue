<template>
    <div class="massege-container">
        <p>{{ msg }}</p>
    </div>
</template>

<script>

export default {
    name: "Message",
    props: {
        msg: String
    }
}
</script>

<style scoped>
.massege-container {
    color: #004085;
    background-color: #cce5ff;
    border: 2px solid #b8daff;
    border-radius: 5px;
    padding: 10px;
    max-width: 400px;
    margin: 30px auto;
}
</style>