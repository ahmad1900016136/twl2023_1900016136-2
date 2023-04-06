<template>
  <div class="nav-container">
    <router-link to="/">home</router-link>
    <router-link to="/about">about</router-link>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.nav-container {
    display: flex;
    justify-content: space-around;
    width: 100%;
}
</style>