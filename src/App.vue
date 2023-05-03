<script setup>
// import HelloWorld from "./components/HelloWorld.vue";
// import TheWelcome from "./components/TheWelcome.vue";
import ButtonBtn from "./components/Button.vue";
import Cardcard from "../src/components/Card.vue";
import headerVue from "../src/components/veiw/headerVue.vue";
import footerVue from "../src/components/veiw/footerVue.vue";
import containerVue from "../src/components/veiw/containerVue.vue";

</script>

<template> 

<div class="container">
  <headerVue />
  <containerVue />
  <footerVue />
</div>
</template>

<style>

.container{
  display: flex;
  height: 100vh;
  justify-content: space-between;
  flex-direction: column;
  background-color: rgb(165, 242, 209);

}
</style>
