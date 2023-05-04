<script>
    export default{
        name: "CardComp",
        props:[`propsCard`]
    }
</script>

<template>
    <div>
        <img :src="propsCard.thumb" alt="">
        <h3>{{ propsCard.series }}</h3>
        <h4>{{ propsCard.price }}</h4>
        <h5>{{ propsCard.type }}</h5>
    </div>
</template>

<style lang="scss" scoped>
    div{
        width: calc(100% / 6);
        display: flex;
        align-items: center;
        flex-direction: column;
        h3,
        h4,
        h5{
            font-size: 12px;
            color: white;
            margin-top: 5px;
        }
        img{
            width: 60%;
        }
    }
</style>