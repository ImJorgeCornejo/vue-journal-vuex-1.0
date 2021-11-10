<template>
  <div >
    <img alt="Vue logo" src="../assets/logo.png">
    <h1>My Journal</h1>
    <button class="btn btn-primary" @click="goToDaybook">Primario</button>
    <button class="btn btn-secondary" @click="goToDaybook">Secondario</button>
    <button class="btn btn-success" @click="goToDaybook">Success</button>
 
  </div>
</template>

<script>
export default {
  methods: {
    goToDaybook(){
      this.$router.push({ name: 'no-entry' })
    }
  }
}
</script>


