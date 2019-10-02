<template>
  <div class="flex flex-row m-auto w-full">
    <section class="bg-gray-300 flex flex-col w-1/3 ">
      <div class="flex flex-col ml-5 mr-8 mt-8">
        <span class="text-lg font-medium text-orange-600 mr-4 ml-3 align-middle"
          >Your Name</span
        >
        <input
          class="bg-white focus:outline-none focus:shadow-outline border border-gray-300 rounded-lg py-2 px-4 block w-full appearance-none leading-normal"
          type="email"
          placeholder="Donald Trump"
        />
      </div>
      <div class="flex flex-col mt-8 mb-10 ml-5 mr-8">
        <span class="text-lg font-medium text-orange-600 mr-4 ml-3 align-middle"
          >Your Email</span
        >
        <input
          class="bg-white focus:outline-none focus:shadow-outline border border-gray-300 rounded-lg py-2 px-4 block w-full appearance-none leading-normal"
          type="email"
          placeholder="Trump2020@example.com"
        />
      </div>
    </section>
    <section class="bg-orange-500 w-full text-center">
      <div class="mt-8 flex flex-col text-center ">
        <span class="capitalize text-3xl text-gray-800"
          >start getting free help!</span
        >
          <span class="text-gray-700 text-sm">(Subscribe Motherfucker)</span>
          <button class="bg-blue-600 rounded w-1/6 m-auto mt-5 text-lg font-medium p-1 hover:bg-blue-700 hover:shadow-outline">Help</button>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "DefaultFooter"
};
</script>
