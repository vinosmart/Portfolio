<script setup>
//const
const { hobbies, timeline } = useConstants();
useHead({
  meta: [
    {
      property: "og:site",
      content: "https://www.eazypau.com/about",
    },
  ],
});
</script>
<template>
  <NuxtLayout name="default">
    <div class="about-section">
      <Profile />
      <div class="empty-left-content"></div>
      <div class="right-content">
        <section>
          <h2>About</h2>
          <p class="mt-2">
            Hi there! I'm a self-taught developer with a background in
            mechanical engineering (graduated from Surya group of institutions).
            After discovering my passion for web development, I made a career
            change and became a frontend web developer. Currently working as a
            Software Developer in
            <a
              class="font-bold text-red-600 dark:text-red-300 hover:underline"
              target="blank"
              href="https://fly-social.com/"
              >Zoom local tech pvt ltd</a
            >.
          </p>
          <p class="mt-2">
            I'm passionate in learning new technologies, building responsive
            websites, and documenting my working process when it comes to
            complicated features.
          </p>
          <p class="mt-2">
            Here are a few technologies I've been working with recently:
          </p>

          <div class="flex gap-10 pl-3 mt-2">
            <ul>
              <li>JavaScript</li>
              <li>Nuxtjs</li>
              <li>Vue</li>
            </ul>
            <ul>
              <li>Css</li>
              <li>TailwindCSS</li>
              <li>Firebase</li>
            </ul>
          </div>
        </section>

        <section>
          <h2>Career Timeline</h2>
          <CardsCareer v-for="career in timeline" :career-details="career" />
        </section>

        <HobbySection :hobbies="hobbies" />
      </div>
    </div>
  </NuxtLayout>
</template>
