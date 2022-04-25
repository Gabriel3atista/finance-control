<template>
  <div>
    <h1 class="text-lg font-bold">Serviços</h1>
    <nuxt-link to="/servicos/desenvolvimento-de-sites">
      Desenvolvimento de Sites
    </nuxt-link>
    <nuxt-link to="/servicos/marketing-digital">Marketing Digital</nuxt-link>
    <br /><br />
    <nuxt-child />
  </div>
</template>

<script>
export default {
  name: "servicos",

  // middleware() {
  //   console.log("Middleware servicos");
  // },

  data() {
    return {};
  },

  setup() {},

  methods: {},
};
</script>

<style>
</style>