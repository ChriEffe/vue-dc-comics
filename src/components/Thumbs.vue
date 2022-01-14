<template>
    <div class="thumb-container">
        <div class="thumb">
            <img :src="img" :alt="alt">
        </div>
        <span class="caption">{{ title }}</span>
    </div>
</template>

<script>
export default {
    name: 'Thumbs',
    props: ["img", "alt", "title", "type", "price"],
    data(){
        return {

        }
    }
}
</script>

<style lang="scss" scoped>
.thumb-container {
    width: 180px;
}
    .thumb {
        height: 180px;
        width: 180px;
        overflow: hidden;
        margin-bottom: 0.5em;
        img {
            width: 100%;
        }
    }
    .caption {
        text-transform: uppercase;
        font-size: 0.8em;
        color: white;
    }
</style>