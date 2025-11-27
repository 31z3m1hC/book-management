<template>
  <div id="app">
    <h1>Book Manager</h1>
    <router-view />
  </div>
</template>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    min-height: 100vh;
}

#app {
    padding: 20px;
    min-height: 100vh;
}

h1 {
    color: white;
    text-align: center;
    margin-bottom: 15px;
    font-size: 2.5rem;
    text-shadow: 0 2px 10px rgba(0,0,0,0.2);
}


</style>