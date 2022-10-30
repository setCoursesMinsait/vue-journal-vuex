<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">

    <h1>Hola mundo</h1>

    <button class="btn btn-primary" @click="goToDaybook"> Primary </button>

  </div>
</template>

<script>
export default {
  methods: {
    goToDaybook() {
      this.$router.push({name: 'no-entry'})
    }
  }
}
</script>