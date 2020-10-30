<template>
    <div>
Search
params:{{this.$route.params.keyword}}
<br>

query:{{this.$route.query.keyword1}}
<br>
<br>
params:{{keyword}}
query:{{keyword1}}
    </div>
</template>

<script>
    export default {
        name:'Search',
        props:['keyword','keyword1']
    }
</script>

<style lang="less" scoped>

</style>