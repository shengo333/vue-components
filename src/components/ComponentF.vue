<template>
  <h2>This is last level - component F</h2>
  <h2>component f user name is {{username}}</h2>

</template>

<script>


export default {
    name: 'ComponentF',
    inject: ['username']

}
</script>

<style>

</style>