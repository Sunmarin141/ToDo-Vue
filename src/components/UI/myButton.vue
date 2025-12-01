<template>
    <button><slot></slot></button>
</template>

<script>
    export default {
        name: 'myButton',
    }
</script>

<style scoped>
button{

    font-size: large;
    cursor: pointer;
    display: flex;
    padding: 15px 10px;
    border: 1px solid rgb(19, 138, 19);
    background: none;
}

button:hover{
    background-color: aquamarine;
    transition: 0.3s;
    transform: scale(1.05);
}
</style>