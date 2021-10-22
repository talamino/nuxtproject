<template>
    <h1>main</h1>
</template>


<script>
export default {
  head(){
      return {
        title: 'Aplication Nuxt Posts | Home', 
        meta: [
          {
            hid: "description",
            name: "description",
            content: "Website about posts"
          }
        ],
        htmlAttrs: {
          lang: 'en',
        }
      }
  }
}
</script>