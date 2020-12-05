<template>
  <div class="container mx-auto mt-10">
    <header class="flex justify-between items-center">
      <div style="height: 100px">
        <img src="../assets/hero-logo.png" class="h-full" alt="logo" />
      </div>
      <ul class="flex">
        <li>
          <a
            href="#"
            class="hover:text-green-700 font-medium cursor-pointer p-4 px-3 py-2"
            >Beranda</a
          >
        </li>
        <li>
          <a
            href="#"
            class="hover:text-green-700 font-medium cursor-pointer px-3 py-2"
            >Fitur Produk</a
          >
        </li>
        <li>
          <a
            href="#"
            class="hover:text-green-700 font-medium cursor-pointer px-3 py-2"
            >Harga</a
          >
        </li>
        <li>
          <a
            href="#"
            class="hover:text-green-700 font-medium cursor-pointer px-3 py-2"
            >Resource</a
          >
        </li>
      </ul>
    </header>

    <div class="flex items-center mt-8">
      <div class="w-1/2 py-32">
        <h1 class="text-6xl font-bold leading-tight font-sans">
          Atur waktu anda lebih produktif
        </h1>
        <p class="leading-relax mt-9 text-gray-500 text-xl gap-3">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tenetur iste
          ut veritatis totam enim distinctio praesentium recusandae doloribus
          repellat id?
        </p>
        <a
          href="#"
          class="border-2 bg-green-700 text-white text-base tracking-wide hover:bg-green-600 transition duration-300 cursor-pointer rounded-full py-5 px-8 inline-block mt-8"
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
