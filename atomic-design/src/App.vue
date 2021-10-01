<template>
  <div class="app">
    <NavItem text="Home" to="/home" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { NavItem } from '@/components/atoms/'

export default defineComponent({
  components: { NavItem }
})
</script>

<style lang="scss" scoped>
.app {
  width: 300px;}
</style>
