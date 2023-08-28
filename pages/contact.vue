<template>
  <div class="container">
    <h3>Untuk keluhan dan masukkan silahkan hubungi kontak berikut</h3>
    <ul class="contact">
      <li><a href="#">Email</a></li>
      <li><a href="#">Instagram</a></li>
      <li><a href="#">Whatsapp</a></li>
    </ul>
  </div>
</template>

<script></script>

<style scoped>
.container {
  width: 700px;
  border-radius: 25px;
  margin: 75px auto;
  text-align: center;
  background-image: url('@/assets/kayu.jpg');
}

.menu li {
  display: inline-block;
}
.menu li:last-child a {
  font-size: 20px;
  color: salmon;
  font-weight: bold;
}
.menu li a {
  color: #333;
  font-size: 18px;
  text-decoration: none;
  float: left;
  width: 130px;
  height: 20px;
  transition: 0.5s;
  padding: 10px;
}

.menu li a:hover {
  font-size: 22px;
  color: yellow;
}

.contact {
  text-align: left;
  margin-left: 20px;
}

.contact li {
  height: 40px;
}
.contact li a {
  color: #333;
  font-size: 18px;
  height: 20px;
  margin: 5px;
  text-decoration: none;
  transition: 0.3s;
  line-height: 40px;
}

.contact li:first-child {
  list-style-image: url('~/static/icon/email-icon.png');
}

.contact li:nth-child(2) {
  list-style-image: url('~/static/icon/instagram-icon.png');
}

.contact li:last-child {
  list-style-image: url('~/static/icon/whatsapp-icon.png');
}

.contact li:last-child a:hover {
  font-size: 20px;
  color: #2cb742;
}
.contact li:first-child a:hover {
  font-size: 20px;
  color: #f84437;
}

.contact li:nth-child(2) a:hover {
  font-size: 20px;
  color: #a0379e;
}
</style>
