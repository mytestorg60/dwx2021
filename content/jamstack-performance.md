---
layout: two-cols
background: '#3b9cda'
class: text-background-gray
---

# **JAMStack - Promises**

- <span class="text-background-gray font-extrabold bg-background-ionos rounded p-2 -m-2">Performance</span>
- Security
- Scale
- Availability
- Maintainability
- Portability
- SEO
- Developer Experience
- Editor Experience

::right::

<div class="flex flex-col h-full justify-center">
  <div class="flex items-center m-4 p-4 rounded-lg bg-background-ionos leading-normal text-background-gray">
  Since rendering is done at built time and not at runtime, the time to first byte and consequently the time to first meaningful paint (FMP) is much shorter. In addition static sites are predestined for CDN, that all over the world fast loading times are possible.
  </div>
</div>

<Footer
  title="Copyright © 1&1 IONOS SE 2021"
  :social="[
    { type: 'gh', username: 'ionos-deploy-now' }
  ]"
/>

<IonosLogo left="false" />

<!--
der Webserver der die seite ausleifert muss nur die Assets also HTML JS CSS von der Festplatte oder anderem Storrae laden und ausliefern

die gefühlte performance für den Besucher der Seite hat natürlich dann mit dem verwendeten JS und CSS zu tun, aber meist sollte das schneller sein als der Lamp Stack

mit einem CDN kann man die Seite noch mehr beschleunigen
-->
