<template lang="pug">
    v-app
      v-card.mx-auto(max-width='400')
        v-img.white--text.align-end(height='200px' src='https://cdn.vuetifyjs.com/images/cards/docks.jpg')
          v-card-title Top 10 Australian beaches
        v-card-subtitle.pb-0 Number 10
        v-card-text.text--primary
          div Whitehaven Beach
          div Whitsunday Island, Whitsunday Islands
        v-card-actions
          v-btn(color='orange' text='')
            | Share
          v-btn(color='orange' text='')
            | Explore
</template>

<script>
    import Navbar from "../components/navbar";
    export default {
        name: "home",
        components: {Navbar}
    }
</script>

<style scoped>

</style>
