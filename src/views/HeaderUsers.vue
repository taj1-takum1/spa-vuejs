<template>
  <nav>
    <h2>Users</h2>
    <router-link to="/" class="link" active-class="link--active" exact>Home</router-link>
    <router-link to="/users" class="link" active-class="link--active" exact>Users</router-link>
  </nav>
</template>

<style>
.link {
  margin-right: 10px;
}
.link--active {
  font-size: 20px;
}
</style>
