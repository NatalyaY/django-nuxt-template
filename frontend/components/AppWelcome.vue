<template>
    <div>
        <h1>Заголовок</h1>
        <p>Какой-то текст</p>
        <h2>{{ msg }}</h2>
    </div>
</template>

<script>
export default {
    data() {
        return { msg: 'Тестовое сообщение из state' };
    },
    mounted() {
        console.log('mounted');
    },
};
</script>

<style scoped lang="less">
h1 {
    color: red;
}
</style>
