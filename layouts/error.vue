<template>
  <div id="error" class="h-screen text-center flex flex-col justify-center items-center">
    <p id="errorStatus" class="flex justify-center items-center bg-red-600 text-white text-3xl w-56 h-16 mb-2">{{ error.statusCode }}</p>
    <p id="errorMsg" class="font-bold">{{ error.message }}</p>
  </div>
</template>

<script>
export default {
  layout: 'error_layout',
  props: ['error']
}
</script>
