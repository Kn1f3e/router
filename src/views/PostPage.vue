<template>
  <div>
    <h1>{{ post.title }}</h1>
    <p>{{ post.content }}</p>
    <router-link to="/">На главную</router-link>
  </div>
</template>

<script>
export default {
  data() {
    return {
      post: {},
    };
  },
  mounted() {
    const postId = this.$route.params.id;
    const posts = [
      { id: 1, title: 'Мой первый пост', content: 'Содержимое первого поста.' },
      { id: 2, title: 'Второй пост', content: 'Содержание второго поста.' },
      { id: 3, title: 'Третий пост', content: 'Содержание третьего поста.' },
    ];
    this.post = posts.find((p) => p.id === Number(postId));
  },
  name: 'PostPage'
};
</script>

