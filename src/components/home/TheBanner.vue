<script setup lang="ts">
import { ref } from 'vue'
import TheRating from '../common/TheRating.vue'
import DropdownMenu from '@/components/dropdownMenu/DropdownMenu.vue'
</script>
<template>
  <div class="bg-gray home-banner">
    <div class="container" style="min-height: 600px">
      <DropdownMenu />
    </div>
  </div>
</template>
