<template>
    <div>
        <div class="footer-top">
            <div class="container">
                <div class="col">
                    <h3>dc comics</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                    <h3>SHOP</h3>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>
                <div class="col">
                    <h3>DC</h3>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                        <li><a href="#">Ad Choice</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                <div class="col">
                    <h3>sites</h3>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
                <img class="thumb-bg" src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
        <div class="footer-bottom">
            <div class="social-container">
                <div class="left-col">
                    <button>sign-up now</button>
                </div>
                <div class="right-col">
                    <h2>follow us</h2>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>

            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style lang="scss">
    @import "../assets/scss/style.scss";
    .footer-top {
        width: 100%;
        height: 300px;
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        display: flex;
        align-items: center;
        position: relative;
        z-index: 1;
        .thumb-bg {
            width: 400px;
            position: absolute;
            top: -50px;
            right: 150px;
            z-index: 0;
        }
    }
    .footer-bottom {
        width: 100%;
        height: 100px;
        background-color: #303030;
        position: relative;
        z-index: 1;
        .social-container {
            width: 80%;
            height: 100%;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            .left-col {
                button {
                    border: solid 2px $headingsColor;
                    padding: 10px;
                    background-color: #303030;
                    color: white;
                    text-transform: uppercase;
                }
            }
            .right-col {
                display: flex;
                align-items: center;
                gap: 15px;
                    h2 {
                        color: $headingsColor;
                        font-size: 1em;
                        text-transform: uppercase;
                    }   
            }
            img {
                height: 20%;
            }
        }
    }
    .container {
        display: flex;
        justify-content: start;
        .col {
            width: 15%;
            h3 {
                color: white;
                font-size: 0.8em;
                margin: 8px 0;
                text-transform: uppercase;
            }
            ul {
                list-style: none;
                li {
                    font-size: 0.6em;
                    font-weight: 300;
                    margin: 5px 0;
                    a {
                        text-decoration: none;
                        color: grey;
                    }
                }
            }
        }
    }
</style>