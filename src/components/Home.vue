<template>
  <div>
    <h1>Home</h1>
  </div>
</template>

<script>
export default {
  unmounted() {
    console.log("Home component unmount");
  },
  activated() {
    console.log("component activated");
  },
  deactivated() {
    console.log("component deactivated");
  },
};
</script>
