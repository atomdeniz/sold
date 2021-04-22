<template>
  <div id="app">
    <video-background src="deneme.mp4" style="height: 100vh;">
    </video-background>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import VideoBackground from "vue-responsive-video-background-player";

export default {
  name: "App",
  components: {
    VideoBackground,
  },
};
</script>
