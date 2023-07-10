<script setup>

    const data = 'Welcome to <strong>vue.js 3</strong> master class.'

    function calculateData(n){
      if(n % 2 ==0){
        return "even"
      }
      else{
        return"odd"
      }
    }
    
</script>

<template>
      <div>
        <h1 v-html="data"></h1>
      </div>
</template>

<style scoped>

</style>
