<template>
  <div class="container my-8" style="background-color: #f4e9e2">
    <img src="/kugel.jpg" alt="Andromedar" class="image" />
    <div class="my-3">
      <h2 class="text-2xl my-4">Samples</h2>
      <p class="my-2">You can download a pack with ANDROMEDAR samples.</p>

      <a
        href="https://www.dropbox.com/sh/69rz3ygywc4bu04/AACx1LO3G-ZK26-0CmRI-Wwya?dl=0"
        target="_blank"
        rel="noopener noreferrer"
        class="underline"
        >Download</a
      >
    </div>

    <nuxt-link class="text-xl my-8" to="/">back</nuxt-link>
  </div>
</template>

<script>
export default {}
</script>

<style lang="postcss">
/* Sample `apply` at-rules with Tailwind CSS */
.container {
  @apply min-h-screen flex flex-col items-center text-center mx-auto;
  max-width: 800px;
}

.image {
  @apply;
}
body {
  background-color: #f4e9e2;
}
</style>
