<template>
  <div class="container">
    <h1 class="text-3xl font-bold underline">
      Hello world!
    </h1>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

@import "@/style/main.css";

html {
  font-size: 16px;  
}

html,body{
  margin: 0;
  padding: 0;
}

:root{
  --primary-color: #0F415E;  
}

#app {
  font-family: Poppins, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
  margin: 0;
  width: 100vw;
  height:100vh;

  display: flex;
  align-items: center;
  justify-content: center;
}


</style>
