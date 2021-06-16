---
layout: cover
background: accent1.png
image: ./WWW-Project.png
class: flex flex-col content-start h-full text-background-black
clicks: 3
---

<h1 class="text-center text-background-black "> Architecture of the LAMP-STACK </h1>

<div class="flex items-center flex-col  text-center grow-0 ">
<img v-if="$slidev.nav.clicks === 1" src="/lamp1.svg">
<img v-if="$slidev.nav.clicks === 2" src="/lamp2.svg">
<img v-if="$slidev.nav.clicks === 3" src="/lamp3.svg">



</div>

<style>
h1  {
  font-size: 3em !important;
}
</style>

<Footer
  title="IONOS SE"
  :social="[
    { type: 'gh', username: 'ionos-deploy-now' }
  ]"
/>

<!--
* editors are using the client to gernate the content.
* developers focus on the webserver and database
-->
