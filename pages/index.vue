<template>
  <div class="container" style="background-color: #f4e9e2">
    <img src="/cover.jpg" alt="Andromedar" class="image" />
    <div class="items-center text-center mx-auto">
      <iframe
        style="border: 0; width: 100%; height: 120px"
        class="mx-auto"
        src="https://bandcamp.com/EmbeddedPlayer/album=148200409/size=large/bgcol=333333/linkcol=0f91ff/tracklist=false/artwork=small/transparent=true/"
        seamless
        ><a href="https://andromedar.bandcamp.com/album/andromedar"
          >Andromedar by Andromedar</a
        ></iframe
      >
    </div>
    <div class="flex space-x-8">
      <nuxt-link
        class="text-xl my-8 uppercase hover:underline font-medium"
        to="/sampleus"
        >Sample us</nuxt-link
      >
      <nuxt-link
        class="text-xl my-8 uppercase hover:underline font-medium"
        to="/impressum"
        >Contact / Impressum</nuxt-link
      >
    </div>
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
