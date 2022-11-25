<template>
  <div class="container-grande">
    <div class="logo"> <img src="./img/dc-logo.png" alt=""></div>
    <div class="menu">
      <ul>
        <li>CHARATES</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECIBILES</li>
        <li>VIDEOS</li>
        <li>FAN</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderPage',
};
</script>

<style lang = 'scss' scoped>
.container-grande {
  // background-color: blue;
  display: flex;
  justify-content: space-around;
  height: 20vh;
  align-items: center;
  li {
  display: inline;
  margin: 10px;
  font-size: 10px;
  &:hover{
    color: blue;
    font-size: 20px;
    transition: 1s;

  }
  }
  .logo {
    margin: 20px;
    background-color: white;
  }
}
</style>
