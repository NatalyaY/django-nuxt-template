<!-- eslint-disable vue/multi-word-component-names -->
<template>
    <div>
        <app-header />
        <slot />
        <app-footer />
    </div>
</template>

<script>
import AppHeader from '../components/AppHeader.vue';
import AppFooter from '../components/AppFooter.vue';

export default {
    components: {
        AppHeader,
        AppFooter,
    },
};
</script>
