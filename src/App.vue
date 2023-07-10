<script setup>

    const number = 17

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
        <h1>The number is : {{ number }} / 4 = {{ number/4 }}</h1>
        <h2>The result is:{{ number %2 ==0 ? "even" :"odd" }}</h2>
      </div>
</template>

<style scoped>

</style>
