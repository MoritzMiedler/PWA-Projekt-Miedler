<template>
  <div>
    <Camera :requestAccess="true">
      <div slot="capture" name="capture">Capture</div>
      <div name="fullscreen">Toggle camera in fullscreen</div>
    </Camera>
  </div>
</template>

<script>
import { Camera } from "vue-capture";

export default {
  name: "Home",

  components: { Camera },
};
</script>
