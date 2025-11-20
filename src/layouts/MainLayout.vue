<template>
  <q-layout view="lHh Lpr lFf" class="animated-bg">
    <q-header elevated>
      <q-toolbar>
        <q-btn flat dense round icon="menu" aria-label="Menu" @click="toggleLeftDrawer" />

        <q-toolbar-title>
          <img
            src="../assets/logo.svg"
            srcset="../assets/logo.svg 2x"
            alt="Tagum City Local System Logo"
            style="height: 32px; width: auto; margin-right: 8px; vertical-align: middle"
          />
          TAGUM CITY LOCAL SYSTEM
        </q-toolbar-title>
      </q-toolbar>
    </q-header>

    <q-drawer v-model="leftDrawerOpen" show-if-above bordered class="bg-accent">
      <q-list>
        <q-item-label
          header
          class="text-white text-h6 q-mb-md"
          style="
            background: rgba(0, 0, 0, 0.18);
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
          "
        >
          Navigation
        </q-item-label>
      </q-list>
    </q-drawer>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer elevated>
      <q-toolbar>
        <q-toolbar-title align="center"> © 2025 Tagum City Local System </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const leftDrawerOpen = ref(false);

function toggleLeftDrawer() {
  leftDrawerOpen.value = !leftDrawerOpen.value;
}
</script>

<style lang="scss">
.animated-bg {
  background: repeating-linear-gradient(45deg, #65a046, #65a046 10px, #398411 10px, #398411 20px);
  background-size: auto auto;
  animation: bg-a 2s linear infinite;
}

@keyframes bg-a {
  100% {
    background-position: 0 0;
  }
  0% {
    background-position: 0px 115px;
  }
}
</style>
