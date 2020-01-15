<template lang="pug">
    v-app-bar(color='blue-grey')
      v-app-bar-nav-icon
      v-toolbar-title NuxtNuxtNuxt
      v-spacer
      v-btn(icon='')
        n-link(to="/")
          v-icon mdi-account
      v-btn(icon='')
        n-link(to="/home")
          v-icon mdi-home


</template>

<script>
    import Home from "../pages/home";
    export default {
        name: "navbar",
        components: {Home}
    }
</script>

<style scoped>

</style>
