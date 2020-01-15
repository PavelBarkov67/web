<template lang="pug">
  v-app
    navbar
    login
</template>

<script>
import Index from "../pages/index";
import Navbar from "../components/navbar";
import Login from "../pages/login";
export default {
    components: {Login, Navbar, Index},
    data () {
    return {

    }
  }
}
</script>
