<template>
  <div id="app">
    <!-- App Header -->
    <header class="app-header">
      <h1>Book Manager</h1>
    </header>

    <!-- Main Content -->
    <main class="app-main">
      <router-view />
    </main>

    <!-- App Footer -->
    <footer class="app-footer">
      © 2025 Book Manager • Powered by Vue & Node.js
    </footer>
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
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

/* Header */
.app-header {
  padding: 30px;
  text-align: center;
}
.app-header h1 {
  color: white;
  font-size: 2.5rem;
  text-shadow: 0 2px 10px rgba(0,0,0,0.2);
}

/* Main content */
.app-main {
  flex: 1;
  padding: 20px;
}

/* Footer */
.app-footer {
  text-align: center;
  padding: 15px;
  color: white;
  font-size: 0.9rem;
  background: rgba(0,0,0,0.2);
}
</style>
