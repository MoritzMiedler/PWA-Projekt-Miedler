<template>
  <div>
    <camera :requestAccess="true"></camera>
  </div>
</template>

<script>
import { camera } from "vue-capture";

export default {
  name: "Home",

  components: { camera },
};
</script>
