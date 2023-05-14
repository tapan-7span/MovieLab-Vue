<template lang="">
  <div>
    <Logo></Logo>
    <Button name="Home"></Button>
    <Button name="Movies"></Button>
    <Button name="Projects"></Button>
  </div>
</template>
<script>
import Button from "../components/NavBar/Button.vue";
import Logo from "../components/NavBar/Logo.vue";
import HollyWood from "./Movies/HollyWood.vue";
export default {
  components: {
    Logo,
    Button,
    HollyWood,
  },
};
</script>
<style lang=""></style>
