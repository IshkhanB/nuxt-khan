<template>
  <div>
  <img src="/favicon.ico" alt="favicon">

  <h1>Hello from index Page</h1>
  <h2>Hello from index Page</h2>
  <!-- <MenuAppAlert></MenuAppAlert> -->
  <!-- <AppAlert></AppAlert> -->
  </div>

</template>

<script setup lang="ts">
const data = ref('')

data.value = await useFetch('http://localhost:3000/nuxt-khan/about/us') as unknown as string

// .then((resp)=resp.text())
// .then(data=>console.log(data))
// .catch((e)=>console.log(e))

//   definePageMeta({
//   pageTransition: {
//     name: 'rotate'
//   }
// })
</script>