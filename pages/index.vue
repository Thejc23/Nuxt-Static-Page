<template>
  <div>
    <Logo Logo=""></Logo>
    <ContentContainerComponent />
    <section class="bg-gray-100 mt-10 text-center pb-10">
      <h1 class="font-medium text-4xl text-orange-500 italic font-serif pt-4 ">
        Categories
      </h1>
      <div class="container flex flex-wrap m-auto text-center pt-10 m-auto">
        <CategoriesComponent
          class="m-auto"
          v-for="category in categories"
          :Category="category"
          :key="category.title"
        />
      </div>
    </section>

    <section class="bg-white mt-10 text-center ">
      <h1 class="font-medium text-4xl text-orange-500 italic font-serif pt-4">
        Recent Posts
      </h1>
      <div class="flex flex-wrap px4 m-2 text-left">
        <RecentPostComponent class="mr-auto ml-5" v-for="Recent in 4" />
      </div>
    </section>
  </div>
</template>

<script>
import Logo from "~/components/HomeComponents/LogoContainerComponent";
import ContentContainerComponent from "../components/HomeComponents/ContentContainerComponent";
import CategoriesComponent from "../components/HomeComponents/CategoryComponent";
import RecentPostComponent from "../components/HomeComponents/RecentPostComponent";
export default {
  components: {
    RecentPostComponent,
    CategoriesComponent,
    ContentContainerComponent,
    Logo
  },
  data() {
    return {
      categories: [
        { image: "", title: "Backend" },
        { image: "", title: "Frontend" },
        { image: "", title: "UI/UX" }
      ]
    };
  }
};
</script>
