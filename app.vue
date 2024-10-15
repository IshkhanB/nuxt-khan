<template>
<nav>
<NuxtLink to="http://localhost:3000/about">About </NuxtLink>
<br>
<NuxtLink to="http://localhost:3000">Home</NuxtLink>
</nav>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>

  </div>
</template>

<style lang="scss">
@import url("~/assets/css/style.scss");
h1 {
  font-family: 'FarAwayGalaxy', sans-serif;
}
</style>
