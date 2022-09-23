<template>
    <div class="">
        <div class="relative ">
          <div
            class="pointer-events-auto h-6 w-10 rounded-full p-1 ring-1 ring-inset transition duration-200 ease-in-out bg-slate-900/10 ring-slate-900/5 hover:bg-indigo-600 hover:ring-black/20"
          >
            <div
              class="h-4 w-4 rounded-full bg-white shadow-sm ring-1 ring-slate-700/10 transition duration-200 ease-in-out hover:translate-x-4 "
            ></div>
          </div>
          <div class="z-0">
            <div
              class="absolute left-0 -top-full bottom-2/3 w-px bg-slate-900/[0.2] [mask-image:linear-gradient(to_top,transparent,white_4rem,white_calc(100%-4rem),transparent)]"
            ></div>
          </div>
        </div>
        <label for="toggleB" class="flex items-center cursor-pointer">
    <!-- toggle -->
    <div class="relative">
      <!-- input -->
      <input type="checkbox" id="toggleB" class="sr-only">
      <!-- line -->
      <div class="block bg-gray-600 w-14 h-8 rounded-full"></div>
      <!-- dot -->
      <div class="dot absolute left-1 top-1 bg-white w-6 h-6 rounded-full transition"></div>
    </div>
    <!-- label -->
    <div class="ml-3 text-gray-700 font-medium">
      Toggle Me!
    </div>
  </label>
    </div>
</template>
<script setup>
    const state = ref(false);

</script>
<style>
    /* input:checked ~ .dot {
  transform: translateX(100%);
  background-color: #48bb78;
} */
</style>
