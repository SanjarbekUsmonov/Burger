<template >
  <div>
      <div class="container bg-whiite  row justify-center items-center content-cente">
          <div class="content  row wrap justify-between items-start content-start">
              <div class="con1 row content-center">
                  <div class="upercart bg-white row wrap justify-between items-start content-start">
                      <div class="cart q-mt-md bg-white row justify-center content-center"
                       v-for="cart in carts"
                       :key="cart">
                          <div class="uper bg-white">
                              <div class="img bg-white">
                                   <q-img :src="cart.img"/>
                              </div>
                              <div class="text-h4 q-mt-lg">
                                  {{cart.name}}
                              </div>
                              <div class="q-mt-ml text-body1">
                                 {{cart.text}}
                              </div>
                          </div>
                      </div>
                  </div>
              </div>


              <div class="con2 bg-white row justify-center content-center">
                  <div class="text bg-white">
                      <div class="text-h5 body1">
                          Our Key Features
                      </div>
                      <div class="text-h3 q-mt-md text-weight-bolder">
                        You can easily manage your website
                      </div>
                      <div class="text-body1 q-mt-md">
                        It's crafted with the latest trend of design & coded with all modern approaches. It's a robust & multi-dimensional usable template.
                      </div>
                        <div class="q-mt-md">
                           <q-btn color="black" padding="20px 70px" label="Learn More" />
                           <span class="text-subtitle1 q-ml-md">Talk with us</span>
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
        {img:'https://foodsify.xyz/uploads/service/2021-12-15%2008:48:45_serviceBcftHMpinQ.png',
         name:' Quick Setup',
         text:' You can create your new restaurants website in minutes & if you want you can be our partner.'
        },
        {img:'https://foodsify.xyz/uploads/service/2021-12-15%2008:39:58_serviceoEt1N2dpVQ.png',
         name:'Barcode Print',
         text:' You can create your new restaurants website in minutes & if you want you can be our partner.'
        },
        {img:'https://foodsify.xyz/uploads/service/2021-12-15%2008:56:34_serviceT2a7FrJWwe.png',
         name:' Custom Domain',
         text:'You can add your own domain to your restaurants website. You can also use subdomain.'
        },
        {img:'https://foodsify.xyz/uploads/service/2021-12-15%2009:00:03_serviceBecZkSiJck.png',
         name:'POS System',
         text:'Restaurants owner can create orders by POS. It will work invoice and you can print this invoice.'
        },

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
.con1{
  width: 60%;
  height: 100%;
}
.con2{
  width: 40%;
  height: 100%;
}
.upercart{
  width: 100%;
  height: 80%;
}
.cart{
  width: 47%;
  height: 47%;
  border: 1px solid rgb(225, 225, 225);
  border-radius: 8px;
}
.uper{
  width: 80%;
  height: 80%;
}
.img{
  width: 40%;
  height: 40%;
}
.text{
  width: 92%;
  height: 50%;
}
.text-subtitle1{
  cursor: pointer;
}

</style>
