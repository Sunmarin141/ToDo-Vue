<template>
    <div>
        <ul>
            <li class="active">Все дела</li>
            <li>Завершенные</li>
            <li>Не завершенные</li>
        </ul>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
ul{
    display: flex;
    width: 30%;
    justify-content: space-between;
    margin: 0 auto;
}

li{
    padding: 10px;
    border: 1px solid transparent;
    transition: 0.2s;
    cursor: pointer;
    display: flex;
    list-style-type: none;
}

li.active {
  background-color: #4caf50;
  color: white;
}
</style>