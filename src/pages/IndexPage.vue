<template>
  <div class="row justify-evenly q-pa-md q-mt-xl">
    <a
      class="q-pa-md row items-start"
      href="https://tagumcity.gov.ph/?page_id=631"
      target="_blank"
      style="text-decoration: none"
    >
      <q-card class="my-card">
        <img class="Img" src="../assets/System1.png" />

        <q-card-section>
          <div class="text-h6">Local System 1</div>
          <div class="text-subtitle2">by City Gov of Tagum</div>
        </q-card-section>
      </q-card>
    </a>

    <a
      class="q-pa-md row items-start"
      href="https://umtc.umindanao.edu.ph/login"
      target="_blank"
      style="text-decoration: none"
    >
      <q-card class="my-card">
        <img class="Img" src="../assets/System2.png" />

        <q-card-section>
          <div class="text-h6">Local System 2</div>
          <div class="text-subtitle2">by UM Mindanao</div>
        </q-card-section>
      </q-card>
    </a>

    <a
      class="q-pa-md row items-start"
      href="https://www.discoverdavao.ph/about-tagum-city"
      target="_blank"
      style="text-decoration: none"
    >
      <q-card class="my-card">
        <img class="Img" src="../assets/System4.png" />

        <q-card-section>
          <div class="text-h6">Local System 3</div>
          <div class="text-subtitle2">by Discover Davao</div>
        </q-card-section>
      </q-card>
    </a>

    <a
      class="q-pa-md row items-start"
      href="https://philatlas.com/mindanao/r12/tagum-city.html"
      target="_blank"
      style="text-decoration: none"
    >
      <q-card class="my-card">
        <img class="Img" src="../assets/System3.png" />

        <q-card-section>
          <div class="text-h6">Local System 4</div>
          <div class="text-subtitle2">by PhilAtlas</div>
        </q-card-section>
      </q-card>
    </a>
  </div>
</template>
<script lang="ts"></script>

<style lang="sass" scoped>
.my-card
  width: 100%
  max-width: 250px
  transition: transform 0.2s ease-in-out
  cursor: pointer
  &:hover
    transform: scale(1.05) translateY(-15px)
.Img
  width: 400px
  height: 150px
  object-fit: fit
</style>
