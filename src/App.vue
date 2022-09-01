<template>
  <Header :text="text" />
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
  data(){
    return {
      text: "Ini adalah text dari data"
    }
  }
};
</script>

<style></style>
