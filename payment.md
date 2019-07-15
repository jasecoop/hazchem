---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<div class="fixed w-100 vh-100 b--solid bw5 tc v-mid pointer-events-none z-5"></div>

<div class="pa5">

  <div class="overflow-hidden mb4">
    <div class="fl w-50">
      <h1 class="ma0">Payment</h1>
    </div>
    <div class="w-50 fl tr">
      <img class="ma0" width="200" src="{{ '/assets/images/cc.png' | relative_url }}" />
    </div>
  </div>

  <input class="w-100 mb3 b--solid bw3 bg-orange pa3 f3 black" type="text" placeholder="Card number">
  <input class="w-100 mb3 b--solid bw3 bg-orange pa3 f3 black" type="text" placeholder="Name on card">
  <input class="w-100 mb3 b--solid bw3 bg-orange pa3 f3 black" type="text" placeholder="Expiration date (MM/YY)">
  <input class="w-100 mb3 b--solid bw3 bg-orange pa3 f3 black" type="text" placeholder="Town/City">
  <input class="w-100 mb3 b--solid bw3 bg-orange pa3 f3 black" type="text" placeholder="Security code">

  <a href="/continue.html" class="btn w-100 bg-black orange no-underline pt3 pb3 tc dib f3 ttu">
    Pay now
  </a>

</div>





