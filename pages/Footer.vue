<template>
    <footer>
      <div class="footer-content">
        <p>&copy; {{ currentYear }} My Vue.js App</p>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    data() {
      return {
        currentYear: new Date().getFullYear(),
      };
    },
  };
  </script>
  
  <style scoped>
  footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
  }
  
  .footer-content {
    max-width: 1200px;
    margin: 0 auto;
  }
  </style>
  