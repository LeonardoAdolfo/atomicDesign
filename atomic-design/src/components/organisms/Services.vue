<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas voluptates blanditiis, est eos, nihil officia culpa beatae pariatur nemo soluta, veniam saepe consectetur praesentium perferendis esse mollitia voluptatum adipisci accusamus."
    />
    <Service
      title="BackEnd"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas voluptates blanditiis, est eos, nihil officia culpa beatae pariatur nemo soluta, veniam saepe consectetur praesentium perferendis esse mollitia voluptatum adipisci accusamus."
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quas voluptates blanditiis, est eos, nihil officia culpa beatae pariatur nemo soluta, veniam saepe consectetur praesentium perferendis esse mollitia voluptatum adipisci accusamus."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
