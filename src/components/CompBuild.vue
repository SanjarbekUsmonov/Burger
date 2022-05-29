<template>
  <div>
    <div class="container bg-orange-2 row justify-center items-center content-center">
      <div class="content bg-orange-2   row wrap justify-between items-start content-start">
          <div class="con bg-orange-2 row content-center" >
              <div class="div-center">

                  <div class="text-h3 text-weight-bolder">
                      Build Your Own Website Within Some Minitues.
                  </div>
                  <div class="text-body1 q-mt-lg">
                      Use one platform to sell products to anyone, anywhere—in person with Point of Sale and online through your website, social media, and online marketplaces.
                  </div>
                  <div class="q-mt-lg flex no-wrap">
                    <input class="input" placeholder="Enter your email" type="email">
                    <q-btn color="black" class="q-ml-md" padding="20px 70px" label="Start" />
                  </div>
                  <div class="q-mt-lg text-body1">
                      Try Shopifire free for 14 days, no credit card required. By entering your email, you agree to receive marketing emails from Shopifire.
                  </div>

              </div>
          </div>
          <div class="con2 bg-orange-2 row content-center" >
              <q-img src="https://foodsify.xyz/uploads/hero_img.png"/>
          </div>
      </div>
    </div>
  </div>
</template>
<script>
import { ref } from "vue";
export default {
    setup() {
      return{
        email: ref('')
      }
    }
}
</script>
<style scoped>
.container{
  width: 100%;
  height: 850px;
}
.content{
  width: 85%;
  height: 700px;
}
.con{
  width: 35%;
  height: 100%;
}
.con2{
  width: 57%;
  height: 100%;
}
.div-center{
  width: 100%;
  height: 75%;
}
.input{
  padding: 20px;
  border: none;
  width: 250px;
}
</style>
