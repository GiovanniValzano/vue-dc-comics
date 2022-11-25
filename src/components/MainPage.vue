<template>
  <div>
    <div class="container-nero"> - CONTENT HERE - </div>
    <div class="container-blu">
      <div class="ima">
        <img src="./img/buy-comics-digital-comics.png" alt="">
        DIGITAL COMICS
      </div>
      <div class="ima">
        <img src="./img/buy-comics-merchandise.png" alt="">
        DC MERCHANDAISE
      </div>
      <div class="ima">
        <img src="./img/buy-comics-shop-locator.png" alt="">
        SUBSCRIPTION
      </div>
      <div class="ima">
        <img src="./img/buy-comics-subscriptions.png" alt="">
        COMICH SHOP
      </div>
      <div class="ima">
        <img src="./img/buy-dc-power-visa.svg" alt="">
        DC POWER VISA
      </div>
    </div>
    <div class="parte-dc">
      <div class="box-list">
        <ul>
          <h4>DC COMCIS</h4>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
        </ul>
        <ul>
          <h4>DC</h4>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
        </ul>
        <ul>
          <h4>SITES</h4>
          <li>lorem</li>
          <li>lorem</li>
          <li>lorem</li>
        </ul>
      </div>
      <div><img src="./img/dc-logo-bg.png" alt=""></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainPage',
};
</script>

<style lang = 'scss' scoped>
.container-nero {
  background-color: black;
  height: 10vh;
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
}
.container-blu {
  background-color: rgba(2,130,249,255);
  height: 15vh;
  color: white;
  display: flex;
  justify-content: space-around;
  align-items: center;
  .ima {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 10px;
    gap: 5px;
  }
}
img {
  height: 50px;
}
.parte-dc {
    background-image: url('./img/footer-bg.jpg');
    height: 45vh;
    display: flex;
    color: white;
    justify-content: space-around;
    align-items: center;
    img {
      height: 300px;
    }
    .box-list {
      display: flex;
      gap: 30px;
    }
    ul li {
      list-style-type:none;
      color: gray;
    }
  }
</style>
