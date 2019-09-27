<template>
  <div>
    <Logo Logo="Coding"></Logo>
    <section class="bg-white">
      <div class="container text-center pt-10 m-auto">
        <h1 class="font-medium text-4xl text-orange-500 italic font-serif">
          Learning. Coding. Earning.
        </h1>
        <p class="text-xl text-center text-gray-700 pt-4 ">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad
          minim veniam, quis nostrud exercitation ullamco laboris nisi ut
          aliquip ex ea commodo consequat. Duis aute irure dolor in
          reprehenderit.
        </p>
      </div>

      <div class="container flex pt-5 mx-auto ">
        <div class="inline-block text-center px-4 m-2">
          <img src="/static/images/tool.png" alt="">
        </div>
        <div class="inline-block text-center px-4 m-2">
          <img src="/static/images/code.png" alt="">
        </div>
        <div class="inline-block text-center px-4 m-2">
          <img src="/static/images/file.png" alt="">
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  import Logo from "~/components/HomeComponents/LogoContainerComponent";
  export default {
    components: {
      Logo
    }
  };
</script>
