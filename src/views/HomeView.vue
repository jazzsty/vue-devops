<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <!-- 수정 코드 -->
    <HelloWorld msg="Deploy Test 3" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
