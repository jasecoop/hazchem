---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: checkout
---

<div class="pa2 bg-grey">

  <div class="w-100 mb5 overflow-hidden tc">

    <ul class="progressbar pa0">
      <li>Basket</li>
      <li>Shipping</li>
      <li class="active">Payment</li>
      <li>Confirmation</li>
    </ul>

  </div>


  <div class="demo-card-wide mdl-card mdl-shadow--2dp mx-auto">

    <div class="mdl-card__title">
      <h2 class="mdl-card__title-text">Payment</h2>
    </div>

    <div class="mdl-card__menu">
      <img class="ma0" width="60" src="{{ '/assets/images/cc.png' | relative_url }}" />
    </div>

    <div class="mdl-card__supporting-text">

      <div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label">
        <input autocomplete="cc-number" class="mdl-textfield__input" type="text" id="cc" x-autocompletetype="cc-number">
        <label class="mdl-textfield__label" for="cc">Card Number</label>
      </div>

      <div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label">
        <input class="mdl-textfield__input" type="text" id="cc">
        <label class="mdl-textfield__label" for="cc">Name on card</label>
      </div>

      <div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label">
        <input class="mdl-textfield__input" type="text" id="cc">
        <label class="mdl-textfield__label" for="cc">Expiration date (MM/YY)</label>
      </div>

      <div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label">
        <input class="mdl-textfield__input" type="text" id="name">
        <label class="mdl-textfield__label" for="name">Security code</label>
      </div>

    </div>

    <div class="mdl-card__actions mdl-card--border">
      <a href="/continue.html" class="mdl-button mdl-button--raised mdl-button--colored">
        Buy now
      </a>
    </div>

  </div>

</div>





