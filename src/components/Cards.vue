<script setup lang="ts">
// import { isDark, toggleDark } from '~/composables'
// const search_query = ref('')
// const celtic_cross = ref([])
// const GetCross = async() => {
//   celtic_cross.value = await fetch(`https://rws-cards-api.herokuapp.com/api/v1/cards/random?n=10`)
//     .then(res => res.json())
// }
</script>

<template>
  <div class="p-32 flex border rounded">
    <div class="grid grid-cols-3 grid-rows-3 gap-0">
      <div class="border px-7 py-11 rounded" />
      <div class="border px-7 py-11 rounded">
        01
      </div>
      <div class="border px-7 py-11 rounded" />
      <div class="border px-7 py-11 rounded">
        01
      </div>
      <div class="border px-7 py-11 rounded">
        01
      </div>
      <div class="border px-7 py-11 rounded">
        01
      </div>
      <div class="border px-7 py-11 rounded" />
      <div class="border px-7 py-11 rounded">
        01
      </div>
      <div class="border px-7 py-11 rounded" />
    </div>
    <div class="grid grid-rows-4 gap-0">
      <div class="border px-7 py-11 rounded">
        09
      </div>
      <div class="border px-7 py-11 rounded">
        09
      </div>
      <div class="border px-7 py-11 rounded">
        09
      </div>
      <div class="border px-7 py-11 rounded">
        09
      </div>
    </div>
  </div>
</template>
