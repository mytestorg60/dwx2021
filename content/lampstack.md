---
layout: cover
background: accent1.png
image: ./WWW-Project.png
class: flex flex-col content-start h-full text-background-black
clicks: 3
---

<h1 class="text-center"> Architecture of the LAMP-Stack</h1>

<div class="flex items-center flex-col  text-center grow-0 ">
  <div class="rounded-xl bg-accent-5 p-2">CLIENT</div>
  <mdi:arrow-down-bold class="fill-current text-sm" v-click="1"/>
  <div class="rounded-xl bg-accent-3 p-2" v-click="1">WEBSERVER</div>
  <mdi:arrow-down-bold class="fill-current text-sm" v-click="2"/>
  <div class="rounded-xl bg-accent-2 p-2" v-click="2">DATABASE</div>
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
