<template>
  <h2>This is second level - component E</h2>
  <ComponentF />
</template>

<script>

import ComponentF from './ComponentF.vue'

export default {
    name: 'ComponentE',
    components:{
        ComponentF,
    },
}
</script>

<style>

</style>