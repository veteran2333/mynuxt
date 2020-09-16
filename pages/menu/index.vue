<template>
  <div>
    <h1>menu</h1>
    <nuxt-link to="user">点我</nuxt-link>
    <button @click="$router.back()">back</button>
    <hr>
    <nuxt-child/>
  </div>
</template>

<script>
export default {
  name:"",
  components: {},
  props: {},
  data() {
    return {

    };
  },
  mounted() {
  },
  methods: {

  },
};
</script>

<style  scoped>

</style>
