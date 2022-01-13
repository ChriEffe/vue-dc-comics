<template>
    <header class="container">
        <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li><a href="#">characters</a></li>
            <li class="active"><a href="">comics</a></li>
            <li><a href="#">movies</a></li>
            <li><a href="#">tv</a></li>
            <li><a href="#">games</a></li>
            <li><a href="#">collectibles</a></li>
            <li><a href="#">videos</a></li>
            <li><a href="#">fans</a></li>
            <li><a href="#">news</a></li>
            <li><a href="#">shop</a></li>
        </ul>
    </header>
</template>

<script>
export default {
    name: 'Header',
    data(){
        return {
            title: "Lorem Ipsum"
        }
    }
}
</script>

<style lang="scss" scoped>
header  {
    height: 150px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 0;
    ul  {
        list-style: none;
        display: flex;
        color: black;
        font-weight: bold;
        text-transform: uppercase;
        li  {
            padding: 0 0.5em;
            a  {
                text-decoration: none;
                color: black;
                padding: 64px 0;
                cursor: pointer;
                &:hover,
                &:active,
                &.active  {
                    color: #0282f9;
                    border-bottom: 3px solid #0282f9;
                }
            }
        } 
    }
}
</style>
