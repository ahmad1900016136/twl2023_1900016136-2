<template>
 <div>
  <navbar-component />
  <router-view />
 </div> 
</template>

<script>
import NavbarComponent from './components/NavbarComponent.vue'
export default {
  //register the component
  components :{NavbarComponent}
}
</script>

<style>

</style>
