<template>
  <div class="bg-gray-200 p-3 flex items-center fixed w-full z-10 top-0 left-0">
    <div class="ml-16">
      <img src="./Icons/graduate.svg" alt="" class="w-16" />
    </div>
    <div class="pl-64 items-center">
      <router-link to="/">

        <button class="flex items-center gap-2">
          <img src="./Icons/home-icon.svg" alt="home" class="w-6" />
        </button>
      </router-link >
    </div>
    <div class="ml-20 flex gap-4">
      <h2 class="font-bold">course management</h2>
      <img src="./Icons/Icon material-keyboard-arrow-down.svg" alt="" />
      <h2 class="font-bold">student management</h2>
    </div>
    <div class="ml-auto pr-16 flex gap-4">
      <button class="">log in</button>
      <button>sign up</button>
    </div>
    <router-view></router-view>
  </div>
</template>

<script>
import { RouterLink, RouterView } from 'vue-router';
export default {
components: {RouterLink, RouterView}
}
</script>
