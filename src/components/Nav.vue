<script>
export default{
        name: "AppNav",
        data() {
            return {
                links : [
                  {
                    nome: `Characters`,
                    current: false
                  },
                  {
                    nome: `Comics`,
                    current: false
                  },
                  {
                    nome: `Movies`,
                    current: false
                  },
                  {
                    nome: `TV`,
                    current: false
                  },
                  {
                    nome: `Games`,
                    current: false
                  },
                  {
                    nome: `Collectibles`,
                    current: false
                  },
                  {
                    nome: `Videos`,
                    current: false
                  },
                  {
                    nome: `Fans`,
                    current: false
                  },
                  {
                    nome: `News`,
                    current: false
                  },
                  {
                    nome: `Shop`,
                    current: false
                  }
                ]
            }
        }
    }
</script>

<template>
  <div id="nav">
    <img src="../assets/dc-logo.png" alt="">
    <ul>
      <li v-for="(element, index) in links"><a href="#">{{ element.nome }}</a></li>
    </ul>

  </div>
</template>

<style lang="scss" scoped>
#nav{
  width: 100vw;
  height: 200px;
  background-color: white;
  display: flex;
  align-items: center;
  justify-content: space-around;
  
  ul{
    display: flex;
    justify-content: space-between;
    width: 50%;
    height: 100%;
    margin-bottom: 0;
    li{
      list-style: none;
      height: 100%;
      display: flex;
      align-items: center;
      a{
        text-decoration: none;
        text-transform: uppercase;
        color: black;
        height:100%;
        display: flex;
        align-items: center;
        &:hover{
          border-bottom: 5px solid blue; 
          color: blue;
        }
      }
    }
  }
}

</style>