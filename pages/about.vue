<template>
  <div class="container">
    <h2>
      "Unveiling Worlds" - Membuka dunia-dunia baru melalui halaman-halaman buku
      yang tersedia.
    </h2>
    <p>
      Website ini adalah project pertama yang saya buat, website ini dibuat
      untuk mempermudah pengalaman dalam membaca banyak buku
    </p>
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

.menu li:nth-child(2) a {
  font-size: 20px;
  color: salmon;
  font-weight: bold;
}

.menu li a:hover {
  font-size: 22px;
  color: yellow;
}
</style>
