<template>
  <section class="grd pt-10 firstContainer h-screen">
    <div class="text-center p-64">
      <span class="font-medium text-6xl text-white italic font-serif">{{
        Logo
      }}</span>
      </div>
  </section>
</template>

<script>
export default {
  name: "LogoContainerComponent",
  props: {
    Logo: String
  }
};
</script>

<style scoped>
.grd {
  background: #ffb76b;
  background: -moz-linear-gradient(
    top,
    #ffb76b 0%,
    #ffa73d 28%,
    #ff7c00 85%,
    #ff7f04 100%
  ); /* FF3.6-15 */
  background: -webkit-linear-gradient(
    top,
    #ffb76b 0%,
    #ffa73d 28%,
    #ff7c00 85%,
    #ff7f04 100%
  ); /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(
    to bottom,
    #ffb76b 0%,
    #ffa73d 28%,
    #ff7c00 85%,
    #ff7f04 100%
  ); /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ffb76b', endColorstr='#ff7f04',GradientType=0 ); /* IE6-9 */
}
</style>
