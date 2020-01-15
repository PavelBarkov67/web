<template lang="pug">
  v-app
    v-content
      v-container.fill-height(fluid='')
        v-row(align='center' justify='center')
          v-col(cols='12' sm='8' md='4')
            v-card.elevation-12
              v-toolbar(color='blue-grey' flat='')
                v-toolbar-title Auth
              v-card-text
                v-form
                    v-text-field(label='Login' name='login' prepend-icon='mdi-account' type='text')
                    v-text-field(label='Password' name='password' prepend-icon='mdi-lock' type='password')
              v-card-actions
                v-spacer
                  v-btn(color='blue-grey') Login
</template>

<script>
    export default {
        name: "login"
    }
</script>

<style scoped>

</style>
