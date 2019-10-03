<template>
  <div class="flex flex-col m-auto w-full ">
    <div class="flex flex-row m-auto w-full">
      <section class="bg-gray-900 flex flex-col w-1/2 ">
        <div class="flex flex-col ml-5 mr-8 mt-2">
          <span
            class="text-lg font-medium text-white mr-4 ml-3 align-middle"
            >Your Name</span
          >
          <input
            class="bg-white focus:outline-none focus:shadow-outline border border-gray-300 rounded-lg py-2 px-4 block w-full appearance-none leading-normal"
            type="email"
            placeholder="Donald Trump"
          />
        </div>
        <div class="flex flex-col mt-8 mb-10 ml-5 mr-8">
          <span
            class="text-lg font-medium text-white mr-4 ml-3 align-middle"
            >Your Email</span
          >
          <input
            class="bg-white focus:outline-none focus:shadow-outline border border-gray-300 rounded-lg py-2 px-4 block w-full appearance-none leading-normal"
            type="email"
            placeholder="Trump2020@example.com"
          />
        </div>
      </section>
      <section class="bg-gray-900 w-full text-center">
        <div class="mt-12 flex flex-col text-center ">
          <span class="capitalize text-3xl text-white"
            >start getting free help!</span
          >
          <span class="text-white text-sm">(Subscribe Motherfucker)</span>
          <button
            class="bg-orange-600 rounded w-1/6 m-auto mt-5 text-lg font-medium p-1 hover:bg-orange-700 hover:shadow-lg"
          >
            Help
          </button>
        </div>
      </section>
    </div>
    <section class="text-center bg-gray-200 m-auto w-full">
      <small
        >&copy; Copyright {{ this.year }} GO2CODE. All Rights Reserved</small
      >
    </section>
  </div>
</template>

<script>
export default {
  name: "DefaultFooter",
  data() {
    return {
      year: 0
    };
  },
  created() {
    this.year = new Date().getFullYear();
  }
};
</script>

