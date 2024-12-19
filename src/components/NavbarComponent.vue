<template>
  <nav>
    <router-link to="/">Главная</router-link>
    <router-link to="/post/1">Пост №1</router-link>
    <router-link to="/post/2">Пост №2</router-link>
    <router-link to="/post/3">Пост №3</router-link>
  </nav>
</template>

<script>
export default {
  name: 'NavbarComponent',
};
</script>

  
  <style>
  nav {
    display: flex;
    justify-content: space-around;
    background-color: #00ff8c;
    padding: 1rem;
  }
  a {
    color: rgb(0, 0, 0);
    text-decoration: none;
  }
  </style>
  