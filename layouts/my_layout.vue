<template>
  <div>
    <CustomHeader class="bg-indigo-400" />
    <main class="bg-gray-100">
      <Nav />
      <Nuxt />
    </main>
    <TheFooter />
  </div>
</template>

<script>
import CustomHeader from '@/components/TheHeader'
export default {
  components: {
    CustomHeader
  }
}
</script>