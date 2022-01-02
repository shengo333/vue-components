<template>
  <div>
      <h2>This is Article component</h2>
      <h2>{{title}}</h2>
      <h2>Likes: {{likes}}</h2>
      <h2>published is true - {{isPublished ? 'Yes' : 'no'}}</h2>
  </div>
</template>

<script>
export default {
    name: 'article',
    props: {
        title: {
            tyoe: String,
            required: true,
            default: 'Article Default Title',

        },
        likes: Number,
        isPublished: Boolean,
    }

}
</script>

<style>

</style>