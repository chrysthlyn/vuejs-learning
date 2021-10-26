<template>
  <div class="logos-wrapper">
    <h2 class="title-header">Find Best Logo!</h2>
    <div class="item-logos">
      <img class="logo" src="../assets/facebook-logo.png" alt="Facebook Logo" />
    </div>
    <div class="item-logos">
      <img
        class="logo"
        src="../assets/instagram-logo.png"
        alt="Instagram Logo"
      />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/whatsapp-logo.png" alt="WhatsApp Logo" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/facebook-logo.png" alt="Facebook Logo" />
    </div>
    <div class="item-logos">
      <img
        class="logo"
        src="../assets/instagram-logo.png"
        alt="Instagram Logo"
      />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/whatsapp-logo.png" alt="WhatsApp Logo" />
    </div>
    <div class="item-logos">
      <img class="logo" src="../assets/facebook-logo.png" alt="Facebook Logo" />
    </div>
    <div class="item-logos">
      <img
        class="logo"
        src="../assets/instagram-logo.png"
        alt="Instagram Logo"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "Logos",
};
</script>

<style scoped>
.logos-wrapper {
  width: 60%;
  overflow: hidden;
  margin: auto;
}

.title-header {
  margin-bottom: 80px;
  text-align: left;
}

.item-logos {
  width: 150px;
  height: 150px;
  float: left;
  margin-right: 20px;
  margin-bottom: 20px;
}

.item-logos .logo {
  width: 150px;
  height: 150px;
}
</style>