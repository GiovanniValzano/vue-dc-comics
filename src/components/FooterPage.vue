<template>
  <div>
    <div class="footer">
      <div class="sing">SIGN-UP NOW</div>
      <div class="social">
        <div class="title">FOLLOW US</div>
        <img src="./img/footer-facebook.png" alt="">
        <img src="./img/footer-periscope.png" alt="">
        <img src="./img/footer-pinterest.png" alt="">
        <img src="./img/footer-twitter.png" alt="">
        <img src="./img/footer-youtube.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterPage',
};
</script>

<style lang = 'scss' scoped>
.footer{
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 10vh;
  background-color: rgba(48,48,48,255);
  .sing {
    border: 3px solid blue;
    color: white;
    padding: 1em;
  }
  .social {
    display: flex;
    gap: 10px;
    justify-content: center;
    align-items: center;
  }
  .title {
    color: white;
  }
}
</style>
