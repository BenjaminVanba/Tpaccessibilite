<script setup>
import Header from '../components/MyHeader.vue'
import Footer from '../components/MyFooter.vue'

</script>

<template>
  <Header />
  <div class="aspect-video">
    <iframe class="w-full h-full" src="https://www.youtube.com/embed/EIyixC9NsLI"
      title="Badgers : animated music video : MrWeebl" frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen></iframe>
  </div>
  <div class="bg-neutral-900 text-white mt">
    <h2 class="p-2 text-4xl font-semibold text-white">H2</h2>
  </div>
  <img src="https://www.peta.org/wp-content/uploads/2019/03/badger-2030975_1920.jpg" alt="beautiful badger"
    class="object-cover w-full max-h-64">
  <div class="bg-neutral-900 text-white mt">
    <h2 class="p-2 text-4xl font-semibold text-white">H2</h2>
  </div>
  <div class="bg-gray-400 m-3 p-3">
    <div class="grid lg:grid-cols-3 md:grid-cols-2 sm:grid-cols-1 gap-4">
      <div>
        <h3>Titre A</h3>
        <p class="text-red-700">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vitae repudiandae
          laborum pariatur, temporibus ut fuga molestias est a sint magni esse harum et placeat atque facilis.
          Pariatur corrupti officia laborum.</p><a href="Lien A" class="bg-neutral-900 text-white p-1 pr-5">
          Lien A
        </a>
      </div>
      <div>
        <h3>Titre B</h3>
        <p class="text-red-700 mb-2">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vitae repudiandae
          laborum pariatur, temporibus ut fuga molestias est a sint magni esse harum et placeat atque facilis.
          Pariatur corrupti officia laborum.</p><a href="Lien B" class="bg-neutral-900 text-white p-1 pr-5">Lien
          B</a>
      </div>
      <div>
        <h3>Titre C</h3>
        <p class="text-red-700">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vitae repudiandae
          laborum pariatur, temporibus ut fuga molestias est a sint magni esse harum et placeat atque facilis.
          Pariatur corrupti officia laborum.</p><a href="Lien C" class="bg-neutral-900 text-white p-1 pr-5">Lien C</a>
      </div>
      <div class="lg:visible invisible text-sky-600">Ce texte n'est visible qu'en vue desktop , en mobile je
        disparais comme un ninja</div>
    </div>
  </div>
  <div class="flex text-center m-3">
    <div class="w-1/2"><button class="bg-gray-950 text-white font-bold py-2 px-4 rounded">
        Button
      </button></div>
    <div class="w-1/2"><button class="bg-gray-950 text-white font-bold py-2 px-4 rounded">
        Button
      </button></div>
  </div>
  <Footer />
</template>
