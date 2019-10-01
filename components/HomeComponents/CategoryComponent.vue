<template>
  <div class="inline-block text-center px-4 m-2">
    <div class="card 1">
      <div class="card_image">
        <img src="~/static/images/undraw_hologram_fjwp.png" />
      </div>
      <div class="card_title ">
        <p class="text-orange-400">{{ Category.title }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CategoriesComponent",
  props: {
    Category: Object
  }
};
</script>

<style scoped>
.cards-list {
  z-index: 0;
  width: 100%;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.card {
  margin: 20px auto;
  width: 300px;
  height: 200px;
  border-radius: 40px;
  cursor: pointer;
  transition: 0.4s;
}

.card .card_image {
  width: inherit;
  height: inherit;
  border-radius: 40px;
}

.card .card_image img {
  width: inherit;
  height: inherit;
  border-radius: 40px;
  object-fit: cover;
}

.card .card_title {
  text-align: center;
  border-radius: 0px 0px 40px 40px;
  font-family: sans-serif;
  font-weight: bold;
  font-size: 25px;
  margin-top: -70px;
  height: 40px;
}

.card:hover {
  transform: scale(0.9, 0.9);
}
</style>
