<script setup lang="ts">
useHead({
  title: "Flix | Movie Reviews",
  link: [
    {
      rel: "icon",
      type: "image/png",
      href: "/logo.png",
    },
  ],
  meta: [
    {
      name: "description",
      content: "Flix is a movie review site",
    },
  ],
});
</script>
<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
