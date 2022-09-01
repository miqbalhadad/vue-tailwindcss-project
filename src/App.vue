<template>
  <Header />
  <Sidebar />
</template>

<script>
import Header from "@/components/Header.vue";
import Sidebar from "@/components/Sidebar.vue";

export default {
  name: "App",
  components: {
    Header,
    Sidebar,
  },
  data() {
    return {
      text: "Ini adalah text dari data",
    };
  },
  methods: {
    ubahText(newText) {
      this.text = newText;
    },
  },
};
</script>

<style></style>
