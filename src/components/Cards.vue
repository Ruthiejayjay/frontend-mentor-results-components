<template>
  <div class="bg-white flex ">
    <div class="h-72 w-56 rounded-3xl back">
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
          <p class="text-xs text-pale-blue opacity-70 para">Your performance exceed 65% of the people conducting the test here!</p>
        </div>
      </div>
    </div>
    <div>
      <h3 class="mt-5">Summary</h3>
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

.para{
  padding-inline: 28px;
}
</style>
