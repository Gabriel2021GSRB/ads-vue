<template>
  
  <div class="app-container">

    <ul>
      <li>• <router-link to="/">Home</router-link></li>
      <li>• <router-link to="Via-Cep">Via Cep</router-link></li>
      <li>• <router-link to="About">Sobre</router-link></li>
    </ul>

    <router-view />

  </div>


</template>

<script setup>

</script>

<style scoped>
.app-container {
  position: fixed;
  top: 0;
  left: 0;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: flex-start;
  padding: 20px;
  box-sizing: border-box;
  z-index: 999; 
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

li {
  margin-bottom: 10px;
  border-bottom: 1px solid rgb(0, 255, 136);
  padding-bottom: 5px; 
}


</style>