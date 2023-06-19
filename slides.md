---
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slide for Pod
drawings:
  persist: false
transition: slide-left
title: Proof of Development
fonts: 
  sans: 'Atkinson Hyperlegible'
  serif: 'IBM Plex Serif'
---

# Welcome to POD

<div class="font-serif">Bridging web3 and the open-source ecosytem</div>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Let's begin <carbon:arrow-right class="inline"/>
  </span>
</div>


<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# What is POD

<p>My Teammates and I discovered a problem:</p>
How do open source contributors get compensated for contributing and how can those contributions be publicly verified. Inspired by Hacktoberfest, POD aims to bridge that gap.
Rewarding open source contributors with NFTs, which act as a public source of truth of contributors credentials.

<div>
  <p>Web3 &lt;- POD -&gt; Open source</p>
  <span>We are the bridge.</span>
</div>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
layout: image-right
image: https://lh3.googleusercontent.com/v6dE4oVLnN1Iv0q3495SurxzRUghRq07WaOE-cy5OVkQozJOujP7moLNsbuFSxoLomNgKA0wTnDrshLgHnd5rMCxcfOt2yNX5wJSM0ajSyck_LK9gJSLmtXeJ0_T-B7IKBHpYk39J7PDPniVIgaRsCWc5BZ3xfUwoYuvQcvIytvX0lHputAixCGlRPMt0Kp9Wx1dJrKyIh03L8yaoJskuC2f7b-Z-hopRs1_-PFmh3KF8bnxApDJ_giCTWYOsE8io38sRFnwqP9L3-xb80rPnF0JWZ4CJzPHg89t9jHgXypwBpVDsMvxRuxsL5T7mNw16_BDEGEyM257oZ4GWzEsFQPQfbxy6BEv2ICijrpj8j1Z48BTGyhtl19nWt-jeLeGvt432YXyJHl87NmMyg4_CfJuSYKnbKA49kqpJqwVCm-iD5Cavv7JEZlRFNxkNK8hTXojYMhKgapJL8EITqw3tSjLJL6tUFaOSaSrwXODhgk4aAc2PbbbZHIYS_xzqhTkO3oBC8XM9qK8R6d2cIjJ9Xx4bBJaAqvWfIOVGO7i3Oyd_EZnLnlCmu9p9CMEhkUQHrIhTeaOFB-onrnfQyMgqkkla9PhwpetvTg5Zygq-M9J7ESck2sjNVJ7dOaUZyvKyHbCmpGP5q9JVZwB-EQ3W47LnOmpJokEmGlmmazW5FpLbWaRc7n8hL4LGrGVnDLT3uoScrQ9Hx4_1CSBSN-y3UlNVvzP-M20YzFSoMn7dKnm0hmptpTWfEP8w-EDItI9OaKEUtNw4eI0K9Kt3bbABBUiSn8Tjk3FPlxO-YG_JdGph9OGcLmMa4Mpq0ffDY-U5u5SN3aObYxBw1kXziqGhCMJonAnZKGqRvthA9S2NdJ0bKP944AA7-0lfr1jvbSKuyx4BD1IGW4f4C5kdNRIufIIv5iX1GQbAUdnPrJPmY4131rq03HsBpqWET_knbWZd-0QPzZxfZyr6v0UcWZx-3tN67nqorM5qykgUPqxF1ZnHBuywygVnN2_6og=w2048-h1365-s-no?authuser=0
---

# Inspiration
<p>Inspired by community:</p>

I attended the largest open source community in Africa called OSCAFest. The experience led me into contemplation of how I could create a public good for web3 contributors and the open source ecosystem. That was our way of contributing to the developer community that has given us so much. the community is why we are here,
we have then created this project to better enable the developer community.

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---
layout: iframe-right
url: https://pod-hackfs.vercel.app/
---
# Solution
<p> what we've built:</p>

Utilizing smart contracts on `FEVM`, storage on `web3Storage` and `IPFS`, `ENS` and various other open source tools, we have created a product, crafted beautifully to onboard open source projects and enable them craft and utilize customized NFTs.

The idea might not be new but our take with an easy to use  UI improves the user experience. UX and UI are paramount in web3.

We also abstract away unnecessary complexity so that users can focus on what matters on the platform.

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# Final thoughts
<p>our plans moving forward</p>

We are very excited about building this public good for the web3 ecosystem. Right now, we have been able to hack on the MVP for HackFS but there is still so much we have planned and we look forward to sharing that with the community.🚀

<div class="text-size-3xl">Thank you for listening! 🎉</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}

</style>
