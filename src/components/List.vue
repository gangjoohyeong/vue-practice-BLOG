<template>
  <div>
    <h5>{{ blogPost[0].title }}</h5>
    <p>{{ blogPost[0].date }}</p>
  </div>
  <div>
    <h5>{{ blogPost[1].title }}</h5>
    <p>{{ blogPost[1].date }}</p>
  </div>
  <div>
    <h5>{{ blogPost[2].title }}</h5>
    <p>{{ blogPost[2].date }}</p>
  </div>
</template>

<script>

export default {
    name : 'List',
    props : {
        blogPost : Object,
    }
}
</script>

<style>

</style>