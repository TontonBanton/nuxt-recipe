<script setup lang="ts">

  defineProps<{
    label?: string,       //Optional - ?:
    to: string            //Required
  }>()

</script>

<template>
  <NuxtLink :to="to" class="px-4 py-2 text-white self-start bg-dodgeroll-gold rounded-md text-base lg:text-lg cursor-pointer">
    {{ label }}
  </NuxtLink>
</template>
