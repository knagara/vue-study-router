<template>
    <div>
        <h2>Users</h2>
        <router-link to="/users/1">User1</router-link>
        <router-link to="/users/2">User2</router-link>
        <hr>
        <!-- <h3>User No. {{ $route.params.id }}</h3> -->
        <h3>User No. {{ id }}</h3>
    </div>
</template>

<script>
export default {
    props: ['id'],
    watch: {
        $route(to, from){
            console.log(from);
            console.log(to);
            console.log("route change")
        }
    }
}
</script>