<template>
  <div>
    <h1 class="text-lg font-bold">A empresa</h1>
    <p>
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ea aliquam
      praesentium reprehenderit facere fuga fugit et, obcaecati quasi? Porro,
      recusandae sunt explicabo facere quo illum voluptas adipisci nam quasi
      laborum.
    </p>
  </div>
</template>

<script>
export default {
  name: "a-empresa",

  middleware: 'auth',

  // middleware() {
  //   console.log("Middleware a empresa");
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