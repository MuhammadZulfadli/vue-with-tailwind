<template>
  <div class="container mx-auto mt-10">
    <header class="flex justify-between items-center">
      <div style="height: 45px">
        <img src="../assets/logo.png" class="h-full" alt="logo" />
      </div>
      <ul class="flex">
        <li>
          <a
            href="#"
            class="hover:text-green-500 font-medium cursor-pointer p-4 px-3 py-2"
            >Home</a
          >
        </li>
        <li>
          <a
            href="#"
            class="hover:text-green-500 font-medium cursor-pointer px-3 py-2"
            >About</a
          >
        </li>
        <li>
          <a
            href="#"
            class="hover:text-green-500 font-medium cursor-pointer px-3 py-2"
            >Service</a
          >
        </li>
        <li>
          <a
            href="#"
            class="hover:text-green-500 font-medium cursor-pointer px-3 py-2"
            >Portfolio</a
          >
        </li>
        <li>
          <a
            href="#"
            class="hover:text-green-500 font-medium cursor-pointer px-3 py-2"
            >Contact</a
          >
        </li>
      </ul>
    </header>

    <div class="flex items-center mt-8">
      <div class="w-1/2 p-24 py-32">
        <h1 class="text-8xl font-bold leading-none font-sans">
          Our Service For You
        </h1>
        <p class="leading-relax mt-5 text-gray-500">
          Contrary to popular belief, Lorem Ipsum is not simply random text. It
          has roots in a piece of classical Latin literature from 45 BC, making
          it over
          <strong>2000</strong> years old. Richard McClintock, a Latin professor
          at Hampden-Sydney College in Virginia, looked up one of the more
          obscure Latin words, consectetur, from a Lorem Ipsum passage, and
          going through the cites of the word in classical literature,
          discovered the undoubtable source.
        </p>
        <a
          href="#"
          class="border-2 bg-green-500 text-white text-base tracking-wide hover:bg-green-600 transition duration-300 cursor-pointer rounded-full py-1.5 px-8 inline-block mt-8"
          >Learn More</a
        >
      </div>
      <div class="w-17/2">
        <img src="../assets/hero.png" alt="hero" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
