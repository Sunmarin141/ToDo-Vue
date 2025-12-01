<template>
    <input 
    :placeholder="placeholder"
    type="text">
</template>

<script>
    export default {
        name:'myInput',
        props:{
            placeholder: String,
        }
    }
</script>

<style scoped>
input{
    padding: 10px;
    font-size: large;
    border: 1px solid green;
    width: 100%;
    outline: none;
    margin-bottom: 15px;
}
</style>