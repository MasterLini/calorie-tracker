<template>
  <div class="login-container">
    <form @submit.prevent="onSubmit">
      <input type="email" v-model="email" placeholder="E-Mail" />
      <input type="password" v-model="password" placeholder="Passwort" />
      <button type="submit">Anmelden</button>
      <button type="button">Registrieren</button>
    </form>
  </div>
</template>

<script>
</script>

<style scoped>

</style>
