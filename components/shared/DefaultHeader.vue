<template>
  <div class="bg-white h-auto fixed w-full">
    <section class="pl-10">
      <div class="flex flex-row">
        <div class="text-left">
          <nuxt-link
            to="/"
            class="font-bold text-4xl pr-4 mt-auto hover:bg-orange-500 mb-2 socials"
          >GO2CODE</nuxt-link>
          <nuxt-link
            to="/blog"
            class="text-base font-medium tracking-widest px-2 mt-auto hover:bg-orange-500 mb-2 socials"
          >Blog</nuxt-link>
          <nuxt-link
            to="/"
            class="text-base font-medium tracking-widest px-2 mt-auto hover:bg-orange-500 mb-2 socials"
          >About</nuxt-link>
          <nuxt-link
            to="/contact"
            class="text-base font-medium tracking-widest px-2 mt-auto hover:bg-orange-500 mb-2 socials"
          >Contact</nuxt-link>
        </div>
        <div class="ml-auto mt-auto mb-2 mr-5">
          <a href>
            <font-awesome-icon :icon="['fab', 'linkedin']" class="mx-2 socials" />
          </a>
          <a href>
            <font-awesome-icon :icon="['fab', 'github']" class="mx-2 socials" />
          </a>
          <a href>
            <font-awesome-icon :icon="['fab', 'facebook']" class="mx-2 socials" />
          </a>
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
.socials {
  color: #3e3c56;
}
</style>
