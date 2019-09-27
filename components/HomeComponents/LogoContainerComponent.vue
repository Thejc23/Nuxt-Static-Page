<template>
  <section class="bg-orange-500 pt-10">
    <div class="text-center p-64">
      <span class="font-medium text-6xl text-white italic font-serif">{{Logo}}</span>
    </div>
  </section>
</template>

<script>
    export default {
        name: "LogoContainerComponent",
      props:{
          Logo:String
      }
    }
</script>


