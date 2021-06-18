---
background: accent2.png
layout: two-cols
class: flex flex-col h-full justify-center text-background-gray
preload: false
---

# Evolution of the web

Over the years web technologies evolved. A great variety of technologies was built up. Some of them are well known, but probably the most of them hardly nobody remembers.

Webpages became more and more dynamic and the html was generated for each request via some programming language. Databases started to be an essential part of the website infrastructure. 



::right::

<div class="flex flex-col h-full justify-center p-4 text-background-gray">
  <div class="absolute top-0 text-6xl font-bold"
    v-motion
    :initial="{ x: -1000, y:0, opacity: 0, scale: 2, rotate: 100 }"
    :enter="{ x: 30, y: 100, opacity: 0.8, scale: 1, rotate: 0, transition: { delay: 500, duration: 1000 } }"
    >
    HTML, JS, CSS
  </div>
  <div class="absolute top-0 text-2xl font-bold"
    v-motion
    :initial="{ x: 1000, y:1000, opacity: 0, scale: 2, rotate: 100 }"
    :enter="{ x: 150, y: 220, opacity: 0.8, scale: 1, rotate: 0, transition: { delay: 500, duration: 1000 } }"
    >
    PHP
  </div>
  <div class="absolute top-0 text-2xl font-bold"
    v-motion
    :initial="{ x: 100, y:-100, opacity: 0, scale: 2, rotate: 100 }"
    :enter="{ x: 200, y: 270, opacity: 0.8, scale: 1, rotate: 0, transition: { delay: 500, duration: 1000 } }"
    >
    Ruby on Rails
  </div>
    <div class="absolute top-0 text-2xl font-bold"
    v-motion
    :initial="{ x: 100, y:-100, opacity: 0, scale: 2, rotate: 100 }"
    :enter="{ x: 150, y: 370, opacity: 0.8, scale: 1, rotate: 0, transition: { delay: 500, duration: 1000 } }"
    >
    Wordpress
  </div>
  <div class="absolute top-0 text-2xl font-bold"
    v-motion
    :initial="{ x: 500, y:-100, opacity: 0, scale: 2, rotate: 100 }"
    :enter="{ x: 50, y: 280, opacity: 0.8, scale: 1, rotate: 0, transition: { delay: 500, duration: 1000 } }"
    >
    NodeJs
  </div>
  <div class="absolute top-0 text-2xl font-bold"
    v-motion
    :initial="{ x: 500, y:-100, opacity: 0, scale: 2, rotate: 100 }"
    :enter="{ x: 70, y: 320, opacity: 0.8, scale: 1, rotate: 0, transition: { delay: 500, duration: 1000 } }"
    >
    LAMP
  </div>
  <div class="absolute top-0 text-2xl font-bold"
    v-motion
    :initial="{ x: 0, y:1000, opacity: 0, scale: 2, rotate: 100 }"
    :enter="{ x: 50, y: 440, opacity: 0.8, scale: 1, rotate: 0, transition: { delay: 500, duration: 1000 } }"
    >
    ... and many others ...
  </div>
</div>

<Footer
  title="IONOS SE"
  :social="[
    { type: 'gh', username: 'ionos-deploy-now' }
  ]"
/>

<!--
-->
