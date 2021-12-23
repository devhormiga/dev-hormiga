<template>
  <div class="bg-black">
    <opening />
    <!-- <site > -->
  </div>
</template>

<script>
import opening from "~/components/opening.vue"
import navbar from "~/components/navbar.vue";
import about from "~/components/aboute.vue";
import buildAbout from "~/components/build-about"
export default {
  components: {
    opening,
    navbar,
    about,
    buildAbout
  },
};
</script>
<style scoped>
  @import 'https://pro.fontawesome.com/releases/v5.10.0/css/all.css';

</style>