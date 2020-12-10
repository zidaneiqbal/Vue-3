<template>
    <div>
        <h1> {{msg}} </h1>
    </div>
</template>

<style scoped>
    h1 {
        color: white;
        padding: 10px 5px;
        background-color: grey;
    }
</style>

<script>
export default {
    name: "First",
    props: {
        msg: String
    }
}
</script>