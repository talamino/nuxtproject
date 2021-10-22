<template>
  <div>
    <h1>About Us</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Explicabo neque
      veniam inventore asperiores, incidunt culpa amet animi optio libero
      magnam.
    </p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Posts | Nuxt App",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Website about posts",
        },
      ],
      htmlAttrs: {
        lang: "en",
      },
    };
  },
};
</script>