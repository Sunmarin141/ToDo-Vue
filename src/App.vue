<template>
    <div>
        <header>
            <PostHeader></PostHeader>
        </header>
        <div class="forma">
            <h1>Добавить занятие</h1>
            <PostForm></PostForm>
        </div>
    </div>
</template>

<script>
import PostForm from './components/PostForm.vue';
import PostHeader from './components/PostHeader.vue';

export default {
    components:{
        PostForm,
        PostHeader
    }
}
</script>

<style>

@font-face {
    font-family: montserrat;
    src: url('components/UI/fonts/Montserrat-Medium.ttf');
}

header{
    margin-top: 5vh;
}

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: montserrat;
}

h1{
    text-align: center;
    margin-bottom: 15px;
}

.forma{
    margin-top: 5vh;
}
</style>