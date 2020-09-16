<template>
  <div>
      params . id
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
      console.log(this.$route.params.id)

  },
  methods: {

  },
};
</script>

<style  scoped>

</style>
