<template>
  <div class="container">
    <div class="construction" > 
      <div class="construction-heading">All Good Things Come to Those who Wait...</div>
      <div class="construction-image">
        <img src="./assets/rocket.svg" alt="">
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

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

.container {
  max-width: 1170px;
  margin: 0 auto;
}

.construction{
  display: flex;
  flex-direction: column;
  align-items: center;
  background-size: 100% auto;
  background-repeat: no-repeat;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
}

.construction-heading{
  width: auto;
  padding-left: 20px;
  padding-right: 20px;
  
  
  font-size: 1.3rem;
  text-align: center;
  color: var(--primary-color)
}

.construction-image{
  margin-top: 50px;
  width: 200px;
}

img{
  max-width: 100%;
}


@media(min-width: 768px){
  
  .construction-heading{  
    font-size: 2.5rem; 
    
  }
  .construction-image{
    width: 100%;
  }
}


@media(min-width: 1367px){
  .construction-heading{  
    font-size: 4.5rem; 
    width: 41.8rem;
    padding-left: 0;
    padding-right: 0;
  }

  .construction{
    flex-direction: row;
  }

  .construction-heading{
    text-align: left;
  }

  .construction-image{
    margin-top: 0;
    width: auto;
  }
}

</style>
