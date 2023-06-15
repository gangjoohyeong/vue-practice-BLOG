<template>
    <h4>상세 페이지</h4>
    <p> {{ blogPost[$route.params.id].title }}</p>
    <p> {{ blogPost[$route.params.id].content }}</p>
    <router-view></router-view>
</template>

<script>
export default {
    name : "Detail",
    props : {
        blogPost : Array,
    }
}
</script>

<style>

</style>