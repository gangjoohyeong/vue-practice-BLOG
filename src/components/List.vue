<template>
  
  <div v-for="(item, index) in blogPost" :key="index">
    <h5 @click="$router.push('/detail/' + index)">{{ item.title }}</h5>
    <p>{{ item.date }}</p>
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