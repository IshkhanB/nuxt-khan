<template>
<header>Заголовок страницы</header>

<nav>Меню навигации</nav>

<aside>Боковая колонка SideBar</aside>

<article>
 Контент - основное содержимое страницы.
</article>

<footer>Подвал сайта</footer>

<nav>
<NuxtLink to="/about">About </NuxtLink>
<br>
<NuxtLink to="/">Home</NuxtLink>
</nav>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>

  </div>
</template>

<style>

</style>
<!-- 
<style lang="scss">
@import url("~/assets/css/style.scss");
h1 {
  font-family: 'FarAwayGalaxy', sans-serif;
}
</style> -->