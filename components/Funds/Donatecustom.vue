<template>
  <div>
    <Script async src="/BTCart-Donate.js"></Script>
    <div class="mt-12"></div>
    <div class="">
      <lightning-donate
        name=""
        :to="lnurl"
        :image="image"
      />
    </div>
  </div>
</template>
<script setup>
import data from "~/config/setup";


const props = defineProps({
  lnurl: String,
  image: String
});


</script>
