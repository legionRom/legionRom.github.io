<template>
  <img
    :src="require('../../logol.png')"
    :width="width"
    alt="logo"
  />
</template>
<script>
export default {
  props: ["width"],
  name: "Logo"
};
</script>
<style></style>
