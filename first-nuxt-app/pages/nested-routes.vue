<template>
    <div>
        <input type="text" v-model="userId">
        <button @click="onLoadUser">Load user</button>

        <nuxt-child />
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
            this.$router.push('/nested-routes/' + this.userId)
            this.userId = "";
            // console.log(this.userId)
        }
    }
}
</script>