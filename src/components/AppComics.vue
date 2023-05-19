<script>

export default {
    props: {
        urlImg: String,
        series: String,
        price: String,
    }
}

</script>

<template>
    <div>
        <img :src="urlImg" :alt="series" />
        <h3>{{ series }}</h3>
    </div>
  
</template>

<style lang="scss" scoped>

</style>
