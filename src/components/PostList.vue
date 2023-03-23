<template>
    <div class="post" v-for="post in posts">  
        <div><strong>Название: </strong>{{ post.title }}</div>
        <div><strong>Описание: </strong>{{ post.body }}</div>
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
.post{
    padding: 15px;
    border:  2px solid teal;
    margin: 15px;
}
</style>

