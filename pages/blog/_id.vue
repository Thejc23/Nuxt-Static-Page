<template>
  <div class="text-center m-auto">
    <section class="text-center m-auto sectionImage w-full " />
    <section class="text-center m-auto">
      <h1 class="text-3xl text-orange-600 mt-8 capitalize">
        Fuckable CSS (TailwindCSS)
      </h1>
      <div class=" w-1/2 w-64 leading-relaxed tracking-wider text-gray-700 text-xl mt-8 text-center antialiased italic  m-auto">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Aliquet enim tortor
        at auctor urna nunc. Pellentesque nec nam aliquam sem et tortor
        consequat. Commodo quis imperdiet massa tincidunt nunc pulvinar sapien.
        Gravida in fermentum et sollicitudin. Quam pellentesque nec nam aliquam
        sem. Eu facilisis sed odio morbi quis commodo odio. Euismod lacinia at
        quis risus sed vulputate. Amet mauris commodo quis imperdiet massa
        tincidunt nunc pulvinar sapien. Viverra accumsan in nisl nisi
        scelerisque eu. Vestibulum lectus mauris ultrices eros in cursus turpis
        massa tincidunt. Aenean et tortor at risus viverra adipiscing at in
        tellus. Scelerisque mauris pellentesque pulvinar pellentesque habitant
        morbi tristique senectus. Integer feugiat scelerisque varius morbi enim
        nunc faucibus. Nibh tortor id aliquet lectus proin nibh. Accumsan sit
        amet nulla facilisi morbi tempus iaculis. Tempor orci dapibus ultrices
        in iaculis nunc sed augue. Lacus sed turpis tincidunt id aliquet risus
        feugiat. In nisl nisi scelerisque eu ultrices vitae. Ipsum dolor sit
        amet consectetur adipiscing elit. Eu volutpat odio facilisis mauris sit
        amet massa vitae tortor. Sollicitudin tempor id eu nisl nunc mi. Quisque
        non tellus orci ac auctor augue mauris augue. Pretium aenean pharetra
        magna ac placerat vestibulum lectus mauris. Odio facilisis mauris sit
        amet massa. Vitae ultricies leo integer malesuada nunc vel risus.
        Tincidunt praesent semper feugiat nibh sed pulvinar proin gravida.
        Lectus quam id leo in vitae turpis massa sed elementum. Sit amet tellus
        cras adipiscing enim. Etiam non quam lacus suspendisse. Congue nisi
        vitae suscipit tellus mauris a. Dolor magna eget est lorem ipsum dolor
        sit. Mi ipsum faucibus vitae aliquet nec ullamcorper sit. Sed cras
        ornare arcu dui vivamus arcu felis. Neque egestas congue quisque
        egestas. Eget sit amet tellus cras adipiscing enim eu turpis. Non tellus
        orci ac auctor augue. Sed egestas egestas fringilla phasellus faucibus
        scelerisque eleifend donec. Adipiscing at in tellus integer feugiat
        scelerisque varius morbi. Condimentum id venenatis a condimentum vitae
        sapien pellentesque. Turpis egestas pretium aenean pharetra magna ac
        placerat vestibulum lectus. Sed tempus urna et pharetra pharetra massa
        massa. Risus feugiat in ante metus dictum at. Dolor sit amet consectetur
        adipiscing elit duis tristique sollicitudin nibh. Eget est lorem ipsum
        dolor sit amet consectetur. Etiam sit amet nisl purus in mollis. Dolor
        sit amet consectetur adipiscing elit ut aliquam purus. Id aliquet lectus
        proin nibh nisl condimentum id. Feugiat sed lectus vestibulum mattis
        ullamcorper. Cursus turpis massa tincidunt dui ut. Sit amet cursus sit
        amet dictum sit. Eget egestas purus viverra accumsan in. Lobortis
        scelerisque fermentum dui faucibus in. Tristique senectus et netus et
        malesuada fames. Ac auctor augue mauris augue neque gravida in. Est
        ullamcorper eget nulla facilisi etiam dignissim diam. Ut morbi tincidunt
        augue interdum velit. Non sodales neque sodales ut. Urna nunc id cursus
        metus aliquam eleifend mi in. Ac orci phasellus egestas tellus rutrum.
        Placerat in egestas erat imperdiet sed euismod nisi porta lorem. Pretium
        aenean pharetra magna ac placerat vestibulum lectus mauris. Amet
        facilisis magna etiam tempor orci eu lobortis elementum nibh. Risus sed
        vulputate odio ut enim blandit volutpat. Molestie a iaculis at erat
        pellentesque. Nullam non nisi est sit amet facilisis magna. Scelerisque
        viverra mauris in aliquam sem fringilla ut. A cras semper auctor neque
        vitae tempus. Orci sagittis eu volutpat odio facilisis mauris. Malesuada
        nunc vel risus commodo viverra maecenas. Vestibulum lectus mauris
        ultrices eros in cursus turpis massa tincidunt. Ultricies integer quis
        auctor elit sed vulputate mi. Tincidunt dui ut ornare lectus sit amet
        est placerat in. Pharetra sit amet aliquam id diam maecenas ultricies.
        Odio eu feugiat pretium nibh ipsum consequat nisl. Vitae ultricies leo
        integer malesuada nunc vel risus commodo. Cursus risus at ultrices mi.
        Volutpat sed cras ornare arcu dui vivamus arcu felis bibendum. Euismod
        in pellentesque massa placerat. Amet cursus sit amet dictum.
      </div>
    </section>
    <section class="bg-white mt-10 text-center  m-auto ">
      <h1 class="font-medium text-2xl text-orange-500 italic font-serif pt-4">
        Recent added
      </h1>
      <div class="flex flex-row px4 text-center m-auto xl:max-w-6xl ">
        <RecentPostComponent class="mr-auto ml-5" v-for="Recent in 2" :key=Recent.id />
      </div>
    </section>
  </div>
</template>

<script>
import RecentPostComponent from "../../components/HomeComponents/RecentPostComponent";
export default {
  components: {RecentPostComponent}
};
</script>

<style scoped>
.sectionImage {
  background-image: url("../../static/images/code.jpeg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  height: 100vh;
}
</style>
