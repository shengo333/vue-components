<template>
  <h2>This is first level - component C</h2>
  <ComponentE />
</template>

<script>

import ComponentE from './ComponentE.vue'

export default {
    name: 'ComponentC',
    components:{
        ComponentE,
    },
}
</script>

<style>

</style>