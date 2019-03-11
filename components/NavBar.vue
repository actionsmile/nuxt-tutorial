<template lang="pug">
    div.nav
        nuxt-link.brand(to="/") Real World Events
        nav
            nuxt-link.button.is-info(to="/") List
            nuxt-link.button.is-warning(to="/create") Create
</template>

<style scoped>
.brand {
    font-weight: 700;
    font-size: 1.5em;
    color: #39b982;
    text-decoration: none;
}
.nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 60px;
}
.nav a {
    display: inline-block;
    margin-right: 10px;
}

.nav a:last-child {
    margin-right: 0px;
}
</style>
