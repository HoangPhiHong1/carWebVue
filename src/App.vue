<script setup>
  import {RouterView} from "vue-router"
  import Nav from "./components/Nav.vue"
  import {ref} from "vue"

</script>

<template>
  <div>
    <Nav/>
    <RouterView/>
  </div>
</template>