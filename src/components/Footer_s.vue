<script>
export default{
        name: "AppFooter_s",
        data() {
            return {
                utility : [
                    {
                        img: "/img/buy-comics-digital-comics.png",
                        text:`DIGITAL COMICS`
                    },
                    {
                        img: "/img/buy-comics-merchandise.png",
                        text:`DC MERCHANDISE`
                    },
                    {
                        img: "/img/buy-comics-subscriptions.png",
                        text:`SUBSCRIPTION`
                    },
                    {
                        img: "/img/buy-comics-shop-locator.png",
                        text:`COMIC SHOP LOCATOR`
                    },
                    {
                        img: "/img/buy-dc-power-visa.svg",
                        text:`DC POWER VISA`
                    }
                ]
            }
        }
    }
</script>

<template>
    <div id="container">
        <div v-for="(element, index) in utility">
            <img :src="element.img" alt="Logo digital comics">
            <span>{{element.text}}</span>
        </div>
    </div>   
</template>

<style lang="scss" scoped>
#container{
    background-color: blue;
    width: 100%;
    height: 200px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 0 2rem;
    z-index: 9;
    position: relative;
    div{
        color: white;
        display: flex;
        align-items: center;
        img{
            width: 70px;
            margin-right: 10px;
        }
    }

}

</style>