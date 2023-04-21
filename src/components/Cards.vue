<script>
import Button from './Button.vue';
export default {
  components: {
    Button
  }
}
</script>

<template>
  <div class="bg-white flex shadow-2xl rounded-3xl card">
    <div class="w-56 rounded-3xl back">
      <div class="mt-5 flex flex-col	
                items-center
                justify-between">
        <h5 class="text-pale-blue text-xl leading-7 mb-5">Your Result</h5>
        <div class="rounded-full w-28 h-28 circle
                      ">
          <h5 class="text-white text-5xl font-extrabold mt-5">76</h5>
          <p class="text-pale-blue opacity-50 text-sm">of 100</p>
        </div>
        <div>
          <h5 class="text-white text-lg font-bold">Great</h5>
          <p class="text-xs text-pale-blue opacity-70 para">Your performance exceed 65% of the people conducting the test
            here!</p>
        </div>
      </div>
    </div>
    <div class="m-5 flex flex-col">
      <h3 class="text-left font-bold">Summary</h3>
      <div class="flex flex-col justify-center">
        <div class="border rounded-lg reaction border-white flex justify-between mt-2">
          <div class="m-2 flex">
          <img src="./..\assets\images\icon-reaction.svg" class="w-4 h-4" alt="">
          <h6 class="text-xs ml-2 text-light-red">Reaction</h6>
          </div>
            <h6 class="text-xs m-2 text-dark-gray-blue"><span class="font-bold">80</span><span class=" opacity-50"> / 100</span></h6>
        </div>
        <div class="border rounded-lg memory border-white flex justify-between mt-2">
          <div class="m-2 flex">
          <img src="./..\assets\images\icon-memory.svg" class="w-4 h-4" alt="">
          <h6 class="text-xs ml-2 text-orangey-yellow">Memory</h6>
          </div>
            <h6 class="text-xs m-2 text-dark-gray-blue"><span class="font-bold">92</span><span class=" opacity-50"> / 100</span></h6>
        </div>
        <div class="border rounded-lg verbal border-white flex justify-between mt-2">
          <div class="m-2 flex">
          <img src="./..\assets\images\icon-verbal.svg" class="w-4 h-4" alt="">
          <h6 class="text-xs ml-2 text-green-teal">Verbal</h6>
          </div>
            <h6 class="text-xs m-2 text-dark-gray-blue"><span class="font-bold">61</span><span class=" opacity-50"> / 100</span></h6>
        </div>
        <div class="border rounded-lg visual border-white flex justify-between mt-2">
          <div class="m-2 flex">
          <img src="./..\assets\images\icon-visual.svg" class="w-4 h-4" alt="">
          <h6 class="text-xs ml-2 text-cobalt-blue">Visual</h6>
          </div>
            <h6 class="text-xs m-2 text-dark-gray-blue"><span class="font-bold">73</span><span class="opacity-50"> / 100</span></h6>
        </div>
      </div>
      <Button class="my-3" />
    </div>
  </div>
</template>

<style scoped>
.back {
  background: linear-gradient(180deg, #7755ff 0%, #6943ff 0.01%, #2f2ce9 100%);
}
.circle {
  background: linear-gradient(180deg, #4D21C9 0%, rgba(37, 33, 201, 0) 100%, rgba(37, 33, 201, 0) 100%);
}
.para {
  padding-inline: 28px;
}
.reaction {
  background: linear-gradient(0deg, rgba(255, 255, 255, 0.95), rgba(255, 255, 255, 0.95)), #FF5555;
}
.memory {
  background: linear-gradient(0deg, rgba(255, 255, 255, 0.95), rgba(255, 255, 255, 0.95)), #FFB21E;
}
.verbal {
  background: linear-gradient(0deg, rgba(255, 255, 255, 0.95), rgba(255, 255, 255, 0.95)), #00BB8F;
}
.visual {
  background: linear-gradient(0deg, rgba(255, 255, 255, 0.95), rgba(255, 255, 255, 0.95)), #1125D6;
}

@media (max-width: 375px) {
  .card {
    display: flex;
    flex-direction: column;
    border-radius: 0px;
  }
  .back {
    border-radius:0px 0px 20px 20px;
  }
  .para {
    padding-bottom: 20px;
  }
}
</style>
