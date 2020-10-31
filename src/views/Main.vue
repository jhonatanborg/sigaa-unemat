<template>
  <div class="home container">
    <div id="menu-bar">
      <AppBar />
    </div>
    <div>
      <Intro />
    </div>
    <div id="views"></div>
  </div>
</template>

<script>
import AppBar from "@/components/shared/AppBar.vue";
import Intro from "@/components/home/Intro.vue";
export default {
  name: "Home",
  components: { AppBar, Intro },
};
</script>
<style></style>
