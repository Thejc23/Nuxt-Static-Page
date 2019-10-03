<template>
  <div class="text-center">
    <h1 class="font-medium text-4xl text-orange-500 italic font-serif pt-10">Posts</h1>
    <div class="flex flex-wrap px4 m-2 text-left xl:max-w-6xl m-auto">

      <RecentPostComponent class="mr-auto ml-5" v-for="(Recent ,index) in 8" :key="index" />
    </div>
  </div>
</template>

<script>
    import RecentPostComponent from "../../components/HomeComponents/RecentPostComponent";
    export default {
        components: { RecentPostComponent }
    };
</script>

<style>
</style>
