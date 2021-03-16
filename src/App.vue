<template>
  <div>
    <nav>
      <router-link to="/" active-class="link--active" exact>Home</router-link>
      <router-link to="/users/1" active-class="link--active" exact>Users</router-link>
    </nav>
    <router-view></router-view>
  </div>
</template>

<style scoped>
  .link--active {
    color: red;
  }
</style>