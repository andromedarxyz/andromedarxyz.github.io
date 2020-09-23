<template>
  <div class="container my-8" style="background-color: #f4e9e2">
    <div class="my-3">
      <p>Booking:</p>
      Michael Maier <br />
      meichel98(a)yahoo.com
    </div>
    <div class="my-3">
      <p>Angaben gemäß § 5 TMG:</p>
      <p>
        Martin Hering<br />
        Deisenhofenerstraße 98<br />
        81539 München<br />
        Kontakt:<br />
        E-Mail: martin.hering.it+andromedar(a)gmail.com <br />Kleinunternehmer
        gemäß § 19 UStG<br />
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
