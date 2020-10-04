<template>
  <div class="container my-8" style="background-color: #f4e9e2">
    <h2 class="text-2xl my-8 font-medium">Booking</h2>
    <div>
      <p class="font-medium">
        Michael Maier <br />
        info@andromedar.xyz
      </p>
    </div>
    <h2 class="text-2xl my-8 font-medium">Impressum</h2>
    <div>
      <p>Angaben gemäß § 5 TMG:</p>
      <p>
        Martin Hering<br />
        Deißenhofenerstraße 98<br />
        81539 München<br />
        martin.hering.it+andromedar(a)gmail.com <br />
        Die Bildrechte liegen bei den jeweiligen Fotografen/Künstler und können
        nur mit deren ausdrücklicher Genehmigung wiederverwendet werden.
      </p>
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
