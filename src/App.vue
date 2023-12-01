<!-- src/App.vue -->
<template>
    <div id="app">
      <about/>
      <PostList />
      <Footer/>
    </div>
  </template>
  
  <script>
  import PostList from './components/PostList.vue';
  import Footer from '../pages/Footer.vue';
  import about from '../components/about.vue';
  
  export default {
    components: {
      PostList,
      Footer,
      about,
    },
  };
  </script>
  
  <style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  
  form {
    margin-top: 10px;
  }
  </style>
  