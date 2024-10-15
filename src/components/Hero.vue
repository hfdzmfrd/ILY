<script setup>
import mainPhoto from "../assets/images/hero.png";
import { themeColor } from "../data/items";

const heroHeading = "I LOVE YOU AYANK EMUAH";
const buttonSeeFeature = "";
const buttonPricing = "";
</script>

<template>
  <div class="untree_co-hero" id="home-section">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-12">
         
          <div class="row align-items-center">
            
            <div class="col-lg">
              <h1 class="heading" data-aos="fade-up" data-aos-delay="0">
                {{ heroHeading }}
              </h1>
              <div class="excerpt" data-aos="fade-up" data-aos-delay="100">
                
              </div>
              
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.pricing:hover {
  color: #fff !important;
}
</style>
