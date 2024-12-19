<template>
  <div>
    <h1>Добро пожаловать в мой блог!</h1>
    <p>Это главная страница блога.</p>
    <ul>
      <li><router-link to="/post/1">Пост №1</router-link></li>
      <li><router-link to="/post/2">Пост №2</router-link></li>
      <li><router-link to="/post/3">Пост №3</router-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>


