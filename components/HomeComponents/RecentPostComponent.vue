<template>
  <a href="/">
    <div>
      <div id="container">
        <div class="product-details">
          <h1 class="text-orange-600 font-medium text-2xl">Biru Putaran</h1>
          <span class="text-center justify-center m-auto text-lg text-gray-700 font-light">
            "Especially good for container gardening, the Angelonia will keep
            blooming all summer even if old flowers are removed."</span
          >
        </div>
        <div class="product-image">
          <img src="~/static/images/code.jpeg" alt="CodingSantana" />
        </div>
      </div>
    </div>
  </a>
</template>

<script>
export default {
  name: "RecentPostComponent"
};
</script>

<style scoped>
body {
  background: #dfc2f2;
  background-image: linear-gradient(135deg, #ce9ffc 10%, #7367f0 100%);
  background-attachment: fixed;
  background-size: cover;
}

#container {
  background: rgba(255, 255, 255, 0.9);
  text-align: center;
  overflow: auto;
  margin: 5em auto;
  height: 275px;
  width: 500px;
}

/* 	Product details  */
.product-details {
  position: relative;
  text-align: left;
  overflow: scroll;
  padding: 30px;
  height: 100%;
  float: left;
  width: 45%;
}

/* product image  */
.product-image {
  transition: all 0.3s ease-out;
  display: inline-block;
  position: relative;
  overflow: hidden;
  height: 100%;
  float: right;
  width: 55%;
  display: inline-block;
}

#container img {
  width: 100%;
  height: 100%;
}

.info {
  background: rgba(27, 26, 26, 0.9);
  font-family: "Farsan", cursive;
  transition: all 0.3s ease-out;
  transform: translateX(-100%);
  position: absolute;
  line-height: 1.9;
  text-align: left;
  font-size: 120%;
  cursor: no-drop;
  color: #fff;
  height: 100%;
  width: 100%;
  left: 0;
  top: 0;
}

.info h2 {
  text-align: center;
}
.product-image:hover .info {
  transform: translateX(0);
}

.info ul li {
  transition: 0.3s ease;
}
.info ul li:hover {
  transform: translateX(50px) scale(1.3);
}

.product-image:hover img {
  transition: all 0.3s ease-out;
}
.product-image:hover img {
  transform: scale(1.2, 1.2);
}
</style>
