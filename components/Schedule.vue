<template>
  <div
    class="
      border-r border-gray-400
      md:py-5
      justify-center
      items-center
      flex flex-col
      w-ful
    "
  >
    <span class="text-red-600 sm:text-2xl">{{data.day}}</span>
    <span class="text-gray-800 text-sm sm:text-3xl"><strong>{{data.date.slice(0, 2)}}</strong></span>
    <span class="mt-0 sm:mt-2 text-gray-500 text-sm sm:text-sm">{{data.date.slice(2)}}</span>
    <span class="mt-0 sm:mt-2 font-bold text-sm sm:text-sm"
      >{{data.time}}</span
    >
    <span class="mt-0 sm:mt-2 text-gray-700 text-sm sm:text-sm"
      >{{data.name}}</span
    >
  </div>
</template>

<script>
export default {
  name: "Schedule",
  props: [
    "data"
  ]
};
</script>