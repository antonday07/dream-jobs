<template >
   <header>
        <img src="../assets/images/bg-header-desktop.svg" alt="">
  </header>
</template>
<script lang="ts">

export default {
   
}
</script>
<style lang="scss">
@import "../assets/base.scss";

header {
  background-color: map-get($map: $colors, $key: bgGreen );
  height: 180px;
  img {
    height: 100%;
  
  }
}

</style>