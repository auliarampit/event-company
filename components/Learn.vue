<template>
  <div class="w-8/12 sm:w-3/5 mx-auto">
    <img
      :src="data.image"
      alt=""
      class="w-11/12"
      v-if="data.id === 3"
    />
    
    <img
      :src="data.image"
      alt=""
      class="w-full"
      v-else
    />
    <p class="text-base font-bold sm:text-xl text-center pt-3 pb-2">
      {{data.desc}}
    </p>
    <p class="text-white italic text-base text-center sm:text-lg">
      ({{data.translate}})
    </p>
  </div>
</template>

<script>
export default {
    name: 'Learn',
    props: [
        "data"
    ]
};
</script>

<style>
</style>