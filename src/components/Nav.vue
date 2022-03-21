<template>
  <header>
    <img class="logo" src="@/assets/elemes.png" alt="logo">
    <nav>
      <ul class="nav__links">
        <li><a href="">Home</a></li>
        <li><a href="">About</a></li>
        <li><button class="hot">HOT</button><a href="">Promotions</a></li>
        <li><a href="">Blogs</a></li>
        <li><a href="">Contact Us</a></li>
      </ul>
    </nav>
    <a href="" class="in">Masuk</a>
    <a href=""><button class="ds">Daftar Sekarang</button></a>
  </header>
</template>

<script>
export default {
  name: 'Nav',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import '../assets/css/style.css';
.hot{
  width: 36px;
  height: 19px;
  display: block;
  background: #E7462D;
  color:white;
  font-family: 'Rubik';
  font-weight: 700, bold;
  font-size: 10px;
  border-radius: 20px;
  border: none;
}
</style>
