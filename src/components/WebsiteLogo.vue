<template>
  <div class="website-logo">
    <img src="../assets/logo.svg" alt="Your next activity">
    <span class="website-name">Activity</span>
  </div>
</template>

<script>
export default {
  name: 'WebsiteLogo',
}
</script>

<style scoped>
.website-logo {
  display: flex;
  align-items: center;
}
.website-name {
  font-family: 'Holtwood One Sc', 'Finlandica', sans-serif;
  margin-left: 5px;
  font-size: 27px;
}
</style>
