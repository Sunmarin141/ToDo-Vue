<template>
    <div class="containerForm">
        <div class="inputs">
            <myInput placeholder="Название дела"></myInput>
            <myInput placeholder="Краткое описание*"></myInput>
        </div>
        <myButton style="justify-self: end;">Создать</myButton>
    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>
.containerForm{
    margin: 0 auto;
    width: 30%;
}
</style>