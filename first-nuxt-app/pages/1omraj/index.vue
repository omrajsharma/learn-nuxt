// defualt url for /omraj route
// First type of routing
// Folder wise routing
<template>
<div>
    <h1>Hello Omraj Sharma</h1>

    <p>insert the url in input box</p>
    <input type="text" v-model="userId">
    <button @click="onLoadUser">Load user</button>
</div>
</template>

<script>
export default {
    data() {
        return {
            userId: ''
        };
    },
    methods: {
        onLoadUser() {
            this.$router.push('/1omraj/' + this.userId)
            console.log(this.userId)
        }
    },
    layout: 'newlay'
}
</script>