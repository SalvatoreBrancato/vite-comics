<script>
export default{
        name: "AppFooter_c",
        data() {
            return {
                
            }
        }
    }
</script>

<template>
  <div id="container">
    <img src="/img/dc-logo-bg.png" alt="logo DC">
    <div class="box">
        <ul>DC COMICS
            <li><a>Characters</a></li>
            <li><a>Comics</a></li>
            <li><a>Movies</a></li>
            <li><a>TV</a></li>
            <li><a>Games</a></li>
            <li><a>Videos</a></li>
            <li><a>News</a></li>
        </ul>
        <ul>SHOP DC
            <li><a>Shop DC</a></li>
            <li><a>Shop DC Collectibles</a></li>
        </ul>
    </div>
    <div class="box">
        <ul>DC
            <li><a>Terms Of Use</a></li>
            <li><a>Privacy Policy</a></li>
            <li><a>Ad Choices</a></li>
            <li><a>Advertising</a></li>
            <li><a>Jobs</a></li>
            <li><a>Subscriptions</a></li>
            <li><a>Talent Workshops</a></li>
            <li><a>TCPSC Certificates</a></li>
            <li><a>Ratings</a></li>
            <li><a>Shop Helps</a></li>
            <li><a>Contacts Us</a></li>
        </ul>
    </div>
    <div class="box">
        <ul>SITES
            <li><a>DC</a></li>
            <li><a>MAD Magazine</a></li>
            <li><a>DC Kids</a></li>
            <li><a>DC Universe</a></li>
            <li><a>DC Power Visa</a></li>
        </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
#container{
    background-image: url(/img/footer-bg.jpg);
    height: 500px;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    position: relative;
    display: flex;
    .box{
        margin-top: 100px;
    }
    img{
        position: absolute;
        right: 100px;
        top: -30px;
    }
    ul{
        color: white;
        font-size: 22px;
        margin-top: 20px;
        margin-left: 20px;
        li{
            color: lightgray;
            list-style: none;
            font-size: 16px;
        }
    }
}

</style>