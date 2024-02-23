<template>
  <div>
    <Head>
      <Title>Towsoft Vina</Title>
      <Meta name="description" content="Towsoft Vina" />
      <Style type="text/css" children="body { background-color: green; }" ></Style>
    </Head>

    <h1>Towsoft Vina</h1>
  </div>
</template>
<script setup lang="ts">
useHead({
  title: 'Towsoft Vina',
  meta: [
    { name: 'description', content: 'Towsoft Vina' }
  ],
  bodyAttrs: {
    class: 'Towsoft Vina'
  },
  script: [ { innerHTML: 'console.log(\'Hello world Towsoft Vina\')' } ]
})
useSeoMeta({
  title: 'Towsoft Vina',
  ogTitle: 'Towsoft Vina',
  description: 'This is Towsoft Vina, let me tell you all about it.',
  ogDescription: 'This is Towsoft Vina, let me tell you all about it.',
  ogImage: 'https://example.com/image.png',
  twitterCard: 'summary_large_image',
})
</script>
