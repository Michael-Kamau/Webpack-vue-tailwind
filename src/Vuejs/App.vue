<template>
  <div>
    <hello-world msg="Hello from my message"/>
  </div>
</template>

<script>
import HelloWorld from "./Components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>
