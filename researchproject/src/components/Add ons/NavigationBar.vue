<template>
    <div class="navbar">
      <div class="navbar-brand">
        <router-link to="/">Your Logo</router-link>
      </div>
      <div class="navbar-menu">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/services">Services</router-link>
        <router-link to="/contact">Contact</router-link>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Navbar',
    // Add any component-specific logic here
  }
  </script>
  
  <style scoped>
  /* Add your custom styles here */
  .navbar {
    background-color: #333;
    color: #fff;
    padding: 10px;
    display: flex;
    justify-content: space-between;
  }
  
  .navbar-brand {
    font-size: 1.5em;
  }
  
  .navbar-menu {
    display: flex;
  }
  
  .router-link {
    margin-right: 10px;
    color: #fff;
    text-decoration: none;
  }
  </style>
  