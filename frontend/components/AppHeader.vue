<template>
    <header>
        <p>Page header</p>
        <NuxtLink to="/">
            Index
        </NuxtLink>
        <NuxtLink to="/about">
            About
        </NuxtLink>
    </header>
</template>

<style scoped lang="less">
    header {
        display: flex;
        align-items: center;
        gap: 30px
    }
</style>
