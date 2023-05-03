<script>
export default{
        name: "AppFooter_s",
        data() {
            return {
                utility : [
                    {
                        img: "../assets/buy-comics-digital-comics.png",
                        text:`DIGITAL COMICS`
                    }
                ]
            }
        }
    }
</script>

<template>
    <div>
        <div v-for="(element, index) in utility">
            <img :src="element.img" alt="Logo digital comics">
            <span>{{element.text}}</span>
        </div>
    </div>   
</template>

<style lang="scss" scoped>
div{
    background-color: blue;
    width: 100vw;
    height: 250px;
}

</style>