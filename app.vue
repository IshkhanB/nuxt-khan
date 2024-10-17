<template>
<!-- <header>Заголовок страницы</header>

<nav>Меню навигации</nav>

<aside>Боковая колонка SideBar</aside>

<article>
 Контент - основное содержимое страницы.
</article>

<footer>Подвал сайта</footer> -->

<nav class="menu">
<NuxtLink to="/about">About </NuxtLink>
<br>
<NuxtLink to="/">Home</NuxtLink>
<br>
<NuxtLink to="/about/us">About/us </NuxtLink>
</nav>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>

  </div>
</template>
<script setup>
const description = ref('Мой невероятный сайт.')

useHead({
  titleTemplate: (titleChunk) => {
    return titleChunk ? `${titleChunk} - Заголовок сайта` : 'Home';
  }
})
</script>

<style>
body{
  text-align: center;
}
.menu{
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
</style>
<!-- 
<style lang="scss">
@import url("~/assets/css/style.scss");
h1 {
  font-family: 'FarAwayGalaxy', sans-serif;
}
</style> -->