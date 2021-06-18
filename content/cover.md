---
layout: cover
background: https://images.unsplash.com/photo-1483401757487-2ced3fa77952?crop=entropy&w=1920
class: text-center
preload: false
---


<div class="flex justify-center">
  <div class="container">
    <h1 class="text-left">  
      <div>
        <span>BACK&lt;&nbsp;</span><br>
        <span>&amp;Future</span>
      </div>
    </h1>
  </div>
</div>

<h2
  v-motion
  :initial="{ x: 1000, opacity: 0, scale: 2, rotate: 100 }"
  :enter="{ x: 0, opacity: 0.8, scale: 1, rotate: 0, transition: { delay: 500, duration: 1000 } }"
  >
The static web returns
</h2>

<Footer class="text-background-gray"
  title="Copyright © 1&1 IONOS SE 2021"
  :social="[
    { type: 'gh', username: 'ionos-deploy-now' }
  ]"
/>

<style scoped>
.container {
  width: 24vw;
  perspective: 20vw;
}

h1, h2 {
  font-family: "BTTF";
  line-height: 100%;
  background: -webkit-linear-gradient(top, red, yellow 40%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke-color: #00F;
  -webkit-text-stroke-width: 1px;
  -webkit-transform: rotateY(15deg);
}
</style>

<!--
<h2
  v-motion
  :initial="{ x: 1000, opacity: 0, scale: 2, rotate: 100 }"
  :enter="{ x: 0, opacity: 0.8, scale: 1, rotate: 0, transition: { delay: 500, duration: 1000 } }"
  >
The static web returns
</h2>
-->