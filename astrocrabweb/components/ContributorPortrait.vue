<template>
  <figure>
      <img :alt="'Black and white portrait of' + navn" :src="bildeUrl">
      <figcaption>{{navn}}</figcaption>
  </figure>
</template>

<script>
export default {
    props: {
      navn: String,
      bildeUrl: String,
    },
}
</script>

<style>
  img {
    max-height: 8em;
    
  }
</style>