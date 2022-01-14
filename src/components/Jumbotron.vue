<template>
    <div class="jumbo"></div>
</template>

<script>
export default {
    name: 'Jumbotron',
    data(){
        return {
            title: "Lorem Ipsum"
        }
    }
}
</script>

<style lang="scss" scoped>
.jumbo  {
    height: 320px;
    background-image: url(../assets/img/jumbotron.jpg);
    background-size: cover;
}
</style>