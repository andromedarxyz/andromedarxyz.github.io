<template>
  <div class="container" style="background-color: #f4e9e2">
    <img src="/cover.jpg" alt="Andromedar" class="image" />
    <iframe
      width="100%"
      height="300"
      scrolling="no"
      frameborder="no"
      allow="autoplay"
      style="padding: 0px 42px"
      src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/1037349952&color=%23000000&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"
    ></iframe>
    <div
      style="
        font-size: 10px;
        color: #cccccc;
        line-break: anywhere;
        word-break: normal;
        overflow: hidden;
        white-space: nowrap;
        text-overflow: ellipsis;
        font-family: Interstate, Lucida Grande, Lucida Sans Unicode, Lucida Sans,
          Garuda, Verdana, Tahoma, sans-serif;
        font-weight: 100;
      "
    >
      <a
        href="https://soundcloud.com/cosmosheldrake"
        title="Cosmo Sheldrake"
        target="_blank"
        style="color: #cccccc; text-decoration: none"
        >Cosmo Sheldrake</a
      >
      ·
      <a
        href="https://soundcloud.com/cosmosheldrake/sets/nightingale-wake-up-calls-1"
        title="Nightingale Wake Up Calls"
        target="_blank"
        style="color: #cccccc; text-decoration: none"
        >Nightingale Wake Up Calls</a
      >
    </div>
    <nuxt-link class="text-xl my-8 uppercase" to="/impressum"
      >Contact / Impressum</nuxt-link
    >
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
