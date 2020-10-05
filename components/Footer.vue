<template>
  <div>
    <section
      id="bottom-navigation"
      class="block fixed inset-x-0 bottom-0 z-10 shadow-2xl"
      style="background-color: #f4e9e2"
    >
      <div id="tabs" class="px-4 footer flex justify-between">
        <nuxt-link class="text-xl my-4 uppercase font-medium" to="/"
          >Home</nuxt-link
        >
        <nuxt-link class="text-xl my-4 uppercase font-medium" to="/sampleus"
          >Sample us</nuxt-link
        >
        <nuxt-link class="text-xl my-4 uppercase font-medium" to="/impressum"
          >Contact</nuxt-link
        >
      </div>
    </section>
  </div>
</template>

<script>
export default {}
</script>

<style lang="postcss" scoped>
.footer {
  /* @apply min-h-screen flex flex-col items-center text-center mx-auto; */
  max-width: 800px;
  margin: auto;
}
</style>
