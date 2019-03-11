<template lang="pug">
    section.container
        div
            logo/
            h1.title.is-1 vuemastery
            h2.subtitle.is-2 My striking Nuxt.js project
            div.links
                a.button.is-primary(
                    href="https://nuxtjs.org/"
                    target="_blank"
                ) Documentation
                |&nbsp;
                a.button(
                    href="https://github.com/nuxt/nuxt.js"
                    target="_blank"
                ) GitHub
</template>

<script>
import Logo from '@/components/Logo.vue';

export default {
    components: {
        Logo
    }
};
</script>
