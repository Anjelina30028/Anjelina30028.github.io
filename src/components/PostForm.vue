<template>
    <div>
        <form @submit.prevent>
            <h1>Создание поста</h1>

            <input class="input" 
            type="text" 
            placeholder="Напиши название">


            <input class="input" 
            type="text" 
            placeholder="Напиши описание">

            <button class="btn" 
            >Добавить</button>
        </form>
    </div>
</template>

<script>
    export default {
    }
</script>

<style scoped>
*{
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
}
.input{
    width: 100%;
    border: 1px solid teal;
    padding: 10px 15px;
    margin: 10px 15px;
}
form{
    display: flex;
    flex-direction: column;
}
.btn{
    margin-top: 15px;
    align-self: flex-end;
    padding: 10px 15px;
    background: none;
    color: teal;
    border: 1px solid teal;
}
</style>