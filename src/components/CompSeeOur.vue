<template >
  <div>
    <div class="container bg-light-blue-1  row justify-center items-center content-cente">
        <div class="content bg-light-blue-1 ">
            <div class="seeour ">
                <div class="text">
                   <div class="text-h3 text-weight-bolder">
                    See Our Themes Lists
                   </div>
                   <div class="text-body1 q-mt-md">
                    Create a food delivery or grocery website backed by powerful tools that help you find customers, drive sales, and manage your day-to-day.Explore More Themes Foodfair
                   </div>
                </div>
            </div>
            <div class="cartbox bg-light-blue-1  row  justify-between items-start content-start">
                <div class="cart bg-white  row justify-center " v-for="cart in carts" :key="cart">
                  <div class="cart-insaid   content-center" >
                      <q-img :src="cart.src"/>
                  </div>
                  <div class="text-h4">
                     {{cart.name}}
                  </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      carts:[
        {src:'https://foodsify.xyz/uploads/demo/demo620e808edc88e2022-02-17%2017:06:22.png',
        name:'Foodfair'},
        {src:'https://foodsify.xyz/uploads/demo/demo620e807ecf2cf2022-02-17%2017:06:06.png',
        name:'Grocery'},
        {src:'https://foodsify.xyz/uploads/demo/demo620e8065f0d552022-02-17%2017:05:41.png',
        name:'GrShop'},
      ]
    }
  },
}
</script>
<style scoped>
 .container{
   width: 100%;
   height: 950px;
 }
 .content{
  width: 85%;
  height: 800px;
}
.seeour{
  width: 100%;
  height: 20%;
}
.text{
  width: 50%;
}
.cartbox{
  width: 100%;
  height: 80%;
}
.cart{
width: 30%;
height: 100%;
border-radius: 10px;
}
.cart-insaid{
  width: 93%;
  height: 87%;
  margin-top: 15px;
}
</style>
