<template>
  <div class="bg-white h-auto fixed w-full">
    <section class="pl-10">
      <div class="flex flex-row">
        <div class="text-left">
          <a
            href=""
            class="font-bold text-4xl pr-4 mt-auto hover:bg-orange-500 mb-2 socials"
            >GO2CODE</a
          >
          <a
            href=""
            class="text-base font-medium tracking-widest px-2 mt-auto hover:bg-orange-500 mb-2 socials"
            >Blog</a
          >
          <a
            href=""
            class="text-base font-medium tracking-widest px-2 mt-auto hover:bg-orange-500 mb-2 socials"
            >About</a
          >
          <a
            href=""
            class="text-base font-medium tracking-widest px-2 mt-auto hover:bg-orange-500 mb-2 socials"
            >Contact</a
          >
        </div>
        <div class="ml-auto mt-auto mb-2 mr-5">
          <a href=""
            ><font-awesome-icon :icon="['fab', 'linkedin']" class="mx-2 socials "
          /></a>
          <a href=""
            ><font-awesome-icon :icon="['fab', 'github']" class="mx-2 socials"
          /></a>
          <a href=""
            ><font-awesome-icon :icon="['fab', 'facebook']" class="mx-2 socials"
          /></a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "DefaultHeader"
};
</script>

<style scoped>
  .socials{
    color: #3E3C56;
  }
</style>
