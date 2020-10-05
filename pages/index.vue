<template>
  <div class="container">
    <img src="/cover.jpg" alt="Andromedar" class="image" />
    <div class="w-full embed px-4">
      <iframe
        style="border: 0; width: 100%; height: 430px"
        src="https://bandcamp.com/EmbeddedPlayer/album=148200409/size=large/bgcol=333333/linkcol=0f91ff/artwork=none/transparent=true/"
        seamless
        ><a href="https://andromedar.bandcamp.com/album/andromedar"
          >Andromedar by Andromedar</a
        ></iframe
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
  @apply min-h-screen flex flex-col items-center text-center mx-auto pt-4 pb-12;
  max-width: 800px;
}
.embed {
  max-width: 700px;
  padding-bottom: 40px;
}

.image {
  @apply;
}

body {
  background-color: #f4e9e2;
}
</style>
