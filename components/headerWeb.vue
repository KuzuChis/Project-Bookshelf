<template>
  <div class="container">
    <ul class="menu">
      <li>
        <router-link to="/">Home</router-link>
      </li>
      <li>
        <router-link to="/about">About</router-link>
      </li>
      <li>
        <router-link to="/contact">Contact</router-link>
      </li>
    </ul>
  </div>
</template>

<style scoped>
body {
  background-color: #eaeaea;
}
* {
  margin: 0px;
  padding: 0px;
}
.container {
  position: fixed;
  left: 0px;
  top: 0px;
  margin: 0px;
  padding: 0px;
  width: 100%;
  height: 50px;
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

.menu li a:hover {
  font-size: 22px;
  color: yellow;
}
</style>
