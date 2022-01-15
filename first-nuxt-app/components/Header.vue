<template>
    <header class="header">
        <ul class="nav-items">
            <li>
                <nuxt-link to="/">Home</nuxt-link>
            </li>
            <li>
                <nuxt-link to="/1omraj">omraj</nuxt-link>
            </li>
            <li>
                <nuxt-link to="/2shyam">shyam</nuxt-link>
            </li>
        </ul>
    </header>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.header {
    width: 100%;
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #eee;
}

.nav-items {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 80%;
}

.nav-items a {
    text-decoration: none;
    color: black;
}

.nav-items a:hover {
    color: green;
}
</style>