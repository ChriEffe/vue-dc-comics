<template>
    <main>
        <div class="main-top">
            <div class="container">
                <h1>--> Content Goes Here</h1>
            </div>
        </div>
        <div class="main-bottom">
            <ul class="container">
                <li class="content">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <p class="caption">digital comics</p>
                </li>
                <li class="content">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <p class="caption">dc merchandise</p>
                </li>
                <li class="content">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <p class="caption">subscriptions</p>
                </li>
                <li class="content">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <p class="caption">dc shop locator</p>
                </li>
                <li class="content">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <p class="caption">dc power visa</p>
                </li>
            </ul>
        </div>
    </main>
</template>

<script>
export default {
    name: 'Main',
    data(){
        return {
            title: "Lorem Ipsum"
        }
    }
}
</script>

<style lang="scss" scoped>
    @import "../assets/scss/style.scss";
    .main-top{
        height: 150px;
        display: flex;
        align-items: flex-start;
        background-color: #1c1c1c;
        }
        h1 {
            color: white;
        }
        .container {
            display: flex;
            justify-content: start;
            align-items: center;
            height: 100%;
        }
        .main-bottom {
            width: 100%;
            height: 150px;
            background-color: $headingsColor;
            text-transform: uppercase;
        }
        .content {
            display: flex;
            justify-content: center;
            width: calc(100% / 5);
            align-items: center;
            gap: 10px;
            img{
            width: 20%;
            }
            .caption {
                font-size: 0.8em;
                color: white;
            }   
        }
</style>