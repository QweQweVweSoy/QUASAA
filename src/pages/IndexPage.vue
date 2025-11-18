<template>
  <div class="row justify-evenly q-pa-md q-mt-xl">
    <div class="q-pa-md row items-start">
      <q-card class="my-card">
        <img class="Img" src="https://i.imgur.com/cZ9xDdi.jpeg" />

        <q-card-section>
          <div class="text-h6">Local System 1</div>
          <div class="text-subtitle2">by Morre</div>
        </q-card-section>
      </q-card>
    </div>

    <div class="q-pa-md row items-start">
      <q-card class="my-card">
        <img class="Img" src="https://i.imgur.com/uLE4dLk.png" />

        <q-card-section>
          <div class="text-h6">Local System 2</div>
          <div class="text-subtitle2">by Musong</div>
        </q-card-section>
      </q-card>
    </div>

    <div class="q-pa-md row items-start">
      <q-card class="my-card">
        <img class="Img" src="https://i.imgur.com/mbUPjsA.png" />

        <q-card-section>
          <div class="text-h6">Local System 3</div>
          <div class="text-subtitle2">by Maedel</div>
        </q-card-section>
      </q-card>
    </div>
  </div>
</template>
<script lang="ts"></script>

<style lang="sass" scoped>
.my-card
  width: 100%
  max-width: 250px
  transition: transform 0.2s
  &:hover
    transform: scale(1.05)
.Img
  width: 400px
  height: 300px
  object-fit: fit
</style>
