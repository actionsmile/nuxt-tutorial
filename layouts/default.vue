<template lang="pug">
    section#app
        nav-bar/
        nuxt/
</template>

<script>
import NavBar from '@/components/NavBar.vue';

export default {
    components: {
        NavBar
    }
};
</script>

<style>
#app {
    box-sizing: border-box;
    width: 500px;
    padding: 0 20px 20px;
    margin: auto;
}
hr {
    box-sizing: content-box;
    height: 0;
    overflow: visible;
}

h1 {
    font-size: 50px;
    font-weight: 700;
}
h2 {
    font-size: 38px;
    font-weight: 700;
}
h3 {
    font-size: 28px;
    font-weight: 700;
}
h4 {
    font-size: 21px;
    font-weight: 700;
}
h5 {
    font-size: 16px;
    font-weight: 700;
}
h6 {
    font-size: 15px;
    font-weight: 700;
}
b,
strong {
    font-weight: bolder;
}
small {
    font-size: 80%;
}
.eyebrow {
    font-size: 20px;
}

.-shadow {
    box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.2), 0 1px 5px 0 rgba(0, 0, 0, 0.13);
}
.badge {
    display: inline-flex;
    height: 26px;
    width: auto;
    padding: 0 7px;
    margin: 0 5px;
    background: transparent;
    border-radius: 13px;
    font-size: 13px;
    font-weight: 400;
    line-height: 26px;
}
.badge.-fill-gradient {
    background: linear-gradient(to right, #16c0b0, #84cf6a);
    color: #fff;
}
label {
    color: rgba(0, 0, 0, 0.5);
    font-weight: 700;
}
input,
textarea {
    box-sizing: border-box;
    border: solid 1px rgba(0, 0, 0, 0.4);
}
textarea {
    width: 100%;
    overflow: auto;
    font-size: 20px;
}
[type="checkbox"],
[type="radio"] {
    box-sizing: border-box;
    padding: 0;
}
[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
    height: auto;
}
[type="search"] {
    -webkit-appearance: textfield;
    outline-offset: -2px;
}
[type="search"]::-webkit-search-decoration {
    -webkit-appearance: none;
}
[type="text"],
[type="number"],
[type="search"],
[type="password"] {
    height: 52px;
    width: 100%;
    padding: 0 10px;
    font-size: 20px;
}
[type="text"]:focus,
[type="number"]:focus,
[type="search"]:focus,
[type="password"]:focus {
    border-color: #39b982;
}
::-webkit-file-upload-button {
    -webkit-appearance: button;
    font: inherit;
}
[hidden] {
    display: none;
}
select {
    width: 100%;
    height: 52px;
    padding: 0 24px 0 10px;
    vertical-align: middle;
    background: #fff
        url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 4 5'%3E%3Cpath fill='%23343a40' d='M2 0L0 2h4zm0 5L0 3h4z'/%3E%3C/svg%3E")
        no-repeat right 12px center;
    background-size: 8px 10px;
    border: solid 1px rgba(0, 0, 0, 0.4);
    border-radius: 0;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
}
select:focus {
    border-color: #39b982;
    outline: 0;
}
select:focus::ms-value {
    color: #000;
    background: #fff;
}
select::ms-expand {
    opacity: 0;
}
.field {
    margin-bottom: 24px;
}
</style>
