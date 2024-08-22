<script setup>
const jsonLd = {
  "@context": "https://schema.org/",
  "@type": "WebSite",
  name: "Web Developer Portfolio | Vinothkumar",
  author: {
    "@type": "Person",
    "@id": "#poyizhi",
  },
  url: "https://www.eazypau.com/",
  description:
    "Personal Portfolio Website. Hi, I am Vinothkumar. I'm a Front-End Web Developer based in Kuala Lumpur, Malaysia. Currently focused on developing website using Vue and React. Checkout my projects and github repositories",
  keywords:
    "Web Developer, Front End Developer, Frontend Developer, Junior Web Developer, Software Developer, Software Engineer, Vinothkumar, Yi Zhi, eazypau, Malaysia",
  image: "https://www.eazypau.com/profile-pics/profile.webp",
};
const personJson = {
  "@context": "https://schema.org/",
  "@type": "Person",
  "@id": "#poyizhi",
  name: "Vinothkumar",
  email: "poyizhi@gmail.com",
  url: "https://www.eazypau.com/",
};
useHead({
  script: [
    {
      children: JSON.stringify(jsonLd),
      type: "application/ld+json",
    },
    {
      children: JSON.stringify(personJson),
      type: "application/ld+json",
    },
  ],
});
definePageMeta({
  layout: false,
});
</script>
<template>
  <NuxtLayout name="main">
    <Header />
  </NuxtLayout>
</template>
