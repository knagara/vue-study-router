<template>
    <div>
        <h1>Home</h1>
        <button @click="toUsers">to users</button>
    </div>
</template>

<script>
export default {
    methods:{
        toUsers(){
            this.$router.push('users/1')
        }
    }
}
</script>