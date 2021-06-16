---
layout: cover
background: blue.png
class: text-center text-background-gray
preload: false 
---

<h1 class="text-background-gray"> Back to the Future</h1>

<h2
  v-motion
  :initial="{ x: 1000, opacity: 0, scale: 2, rotate: 100 }"
  :enter="{ x: 0, opacity: 0.8, scale: 1, rotate: 0, transition: { delay: 500, duration: 1000 } }"
  >
The static web returns
</h2>

<Footer
  title="IONOS SE"
  :social="[
    { type: 'gh', username: 'ionos-deploy-now' }
  ]"
/>

<!--
-->

