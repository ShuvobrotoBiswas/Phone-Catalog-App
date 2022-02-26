<template>
    <div class="q-pa-md">
    <q-carousel
      animated
      v-model="slide"
      infinite
      :autoplay="autoplay"
      arrows
      height="400px"
      width="1200px"
      transition-prev="slide-right"
      transition-next="slide-left"
      @mouseenter="autoplay = false"
      @mouseleave="autoplay = true"
    >
      <q-carousel-slide :name="1" img-src="~assets/img1.png" ref="4">
      <div class="absolute-bottom custom-caption">
          <div class="text-h5">IPhone 13 Pro Max</div>
          <div class="text-subtitle1">From $999
          <q-btn
          icon="shopping_cart"
          label="Buy now"
          href="https://www.apple.com/iphone/"
          />
          </div>
        </div>

      </q-carousel-slide>


      <q-carousel-slide :name="2" img-src="~assets/img2.jpeg">
      <div class="absolute-bottom custom-caption">
          <div class="text-h5">IPhone 13</div>
          <div class="text-subtitle1">From $699
           <q-btn
          icon="shopping_cart"
          label="Buy now"
          href="https://www.apple.com/iphone/"
          />
          </div>
        </div>
        </q-carousel-slide>
      <q-carousel-slide :name="3" img-src="~assets/img3.webp">
      <div class="absolute-bottom custom-caption">
          <div class="text-h2">IPhone 12</div>
          <div class="text-subtitle1">From $599
            <q-btn
          icon="shopping_cart"
          label="Buy now"
          href="https://www.apple.com/iphone/"
          />
          </div>
        </div>
        </q-carousel-slide>
      <q-carousel-slide :name="4" img-src="~assets/img4.jpg">
      <div class="absolute-bottom custom-caption">
          <div class="text-h2">Iphone SE</div>
          <div class="text-subtitle1">From $399
            <q-btn
          icon="shopping_cart"
          label="Buy now"
          href="https://www.apple.com/iphone/"
          />
          </div>
        </div>
        </q-carousel-slide>
    </q-carousel>
  </div>

  <!-- Products -->
  <div class="q-pa-md text-h6">
    IPhones
  </div>

  <div class="q-pa-md">
    <div class="row">
      <!-- <div class="col " >
        <q-img class="imgshuvo" src="~assets/img4.jpg" @click="alert = true">
        <q-dialog v-model="alert">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        IPhone SE
      </div>
        </q-img>
      </div> -->
      <!-- <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp1.jpeg" @click="alert = true">
        <q-dialog v-model="alert">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Caption
      </div>
        </q-img>
      </div> -->
      <!-- <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp2.jpeg" @click="alert = true">
        <q-dialog v-model="alert">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Caption
      </div>
        </q-img>
      </div> -->
      <div class="col " >
        <q-img class="imgshuvo" src="~assets/imgp3.jpeg" @click="alert = true">
        <q-dialog v-model="alert">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
         Brand : Apple <br>
         Model : 11 Pro <br>
         Price : $600 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>

        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Iphone 11 Pro
      </div>
        </q-img>
      </div>
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp4.jpeg" @click="alert1 = true">
        <q-dialog v-model="alert1">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Apple <br>
         Model : 12 Pro <br>
         Price : $650 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Iphone 12 Pro
      </div>
        </q-img>
      </div>
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp5.jpeg" @click="alert2 = true">
        <q-dialog v-model="alert2">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Apple <br>
         Model : 13 Pro <br>
         Price : $700 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Iphone 13 Pro
      </div>
        </q-img>
      </div>
    </div>

    <!-- Section 2 -->

    <div class="row">
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp6.png" @click="alert3 = true">
        <q-dialog v-model="alert3">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Apple <br>
         Model : 11 Pro  Max<br>
         Price : $800 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Iphone 11 Pro Max
      </div>
        </q-img>
      </div>
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp7.jpeg" @click="alert4 = true">
        <q-dialog v-model="alert4">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Apple <br>
         Model : 12 Pro Max <br>
         Price : $1000 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Iphone 12 Pro Max
      </div>
        </q-img>
      </div>
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp8.jpg" @click="alert5 = true">
        <q-dialog v-model="alert5">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Apple <br>
         Model : 13 Pro Max <br>
         Price : $1200 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Iphone 13 Pro Max
      </div>
        </q-img>
      </div>
     </div>

     <!-- Section  3-->

     <div class="q-pa-md text-h6">
      Oneplus Smartphones
      </div>

     <div class="row">
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp9.jpeg" @click="alert6 = true">
        <q-dialog v-model="alert6">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Oneplus <br>
         Model : 11 Pro  <br>
         Price : $800 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Oneplus 11 Pro 
      </div>
        </q-img>
      </div>
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp10.jpeg" @click="alert7 = true">
        <q-dialog v-model="alert7">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Oneplus <br>
         Model : 12 Pro  <br>
         Price : $1000 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Oneplus 12 Pro 
      </div>
        </q-img>
      </div>
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp11.jpeg" @click="alert8 = true">
        <q-dialog v-model="alert8">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Oneplus <br>
         Model : 13 Pro  <br>
         Price : $1200 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Oneplus 13 Pro 
       </div>
        </q-img>
      </div>
     </div>

      <!-- Section 4 -->

      <div class="row">
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp12.jpeg" @click="alert9 = true">
        <q-dialog v-model="alert9">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Oneplus <br>
         Model : 11 Pro  Max<br>
         Price : $800 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Oneplus 11 Pro Max
      </div>
        </q-img>
      </div>
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp13.jpeg" @click="alert10 = true">
        <q-dialog v-model="alert10">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Oneplus <br>
         Model : 12 Pro Max <br>
         Price : $1000 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Oneplus 12 Pro Max
      </div>
        </q-img>
      </div>
      <div class="col">
        <q-img class="imgshuvo" src="~assets/imgp14.jpeg" @click="alert11 = true">
        <q-dialog v-model="alert11">
        <q-card>
        <q-card-section>
          <div class="text-h6">About Phone</div>
        </q-card-section>
        <q-card-section class="q-pt-none">
          Brand : Oneplus <br>
         Model : 13 Pro Max <br>
         Price : $1200 <br>
         Network : 2G, 3G, 4G, 5G <br>
         Sim : E-sim , Nano <br>
         Material : (Front + Back) Gorilla Glass, Frame stainless steel <br>
         Size : 5.8 inches <br>
         Back Camera :  Triple 12 + 12 + 12 Megapixel
        </q-card-section>
        <q-card-actions align="right">
          <q-btn flat label="OK" color="primary" v-close-popup />
        </q-card-actions>
       </q-card>
       </q-dialog>
       <div class="absolute-bottom text-subtitle1 text-center">
        Oneplus 13 Pro Max
      </div>
        </q-img>
      </div>
      </div>

  </div>

  <!-- Header Menu -->

  <div class="q-pa-md">
    <q-header elevated>
        <q-toolbar>
    <q-toolbar-title>
    Phone Catalog App
          </q-toolbar-title>

    <div class="q-gutter-md row items-center">

      <q-btn round icon="menu">
        <q-menu :style="{ backgroundColor: '#eee', color: 'blue'}">
          <q-list dense style="min-width: 100px">
            <q-item clickable v-close-popup>
              <q-item-section>Products</q-item-section>
            </q-item>
            <q-separator />
            <q-item clickable>
              <q-item-section>Category</q-item-section>
              <q-item-section side>
                <q-icon name="keyboard_arrow_left" />
              </q-item-section>

              <q-menu auto-close anchor="top end" self="top start">
                <q-list>
                  <q-item
                    v-for="n in 1"
                    :key="n"
                    dense
                    clickable
                  >
                    <q-item-section>Smartphone</q-item-section>
                    <q-item-section side>
                      <q-icon name="keyboard_arrow_left" />
                    </q-item-section>
                    <!-- <q-menu auto-close anchor="top end" self="top start">
                      <q-list>
                        <q-item
                          v-for="n in 1"
                          :key="n"
                          dense
                          clickable
                        >
                          <q-item-section>IPhones</q-item-section>
                        </q-item>
                      </q-list>
                    </q-menu> -->
                  </q-item>
                </q-list>
              </q-menu>

            </q-item>
            <q-separator />
            <q-item clickable v-close-popup>
              <q-item-section>Quit</q-item-section>
            </q-item>
          </q-list>
        </q-menu>
      </q-btn>


    </div>
    </q-toolbar>
    </q-header>
  </div>
</template>

<script>
import { defineComponent } from "vue";
import { ref } from 'vue'
export default defineComponent({
  name: "PageIndex",
  setup () {
    return {
      // slide: ref('first')
      slide: ref(1),
      autoplay: ref(true),
      alert: ref(false),
      alert1: ref(false),
      alert2: ref(false),
      alert3: ref(false),
      alert4: ref(false),
      alert5: ref(false),
      alert6: ref(false),
      alert7: ref(false),
      alert8: ref(false),
      alert9: ref(false),
      alert10: ref(false),
      alert11: ref(false),
      alert12: ref(false),
      alert13: ref(false),
      alert14: ref(false),
      alert15: ref(false),
      alert16: ref(false),
      alert17: ref(false),
    }
  }
});
</script>
<style lang="sass" scoped>
.custom-caption
  text-align: center
  padding: 12px
  color: white
  background-color: rgba(0, 0, 0, .3)
  .row > div
  padding: 10px 15px
  background: rgba(86,61,124,.15)
  border: 1px solid rgba(86,61,124,.2)
.row + .row
  margin-top: 1rem

.imgshuvo
 height: 200px
 width: 200px
</style>
