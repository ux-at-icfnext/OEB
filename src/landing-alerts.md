---
layout: layouts/base

alert: true

card:
  - title: Are You Eligibile
    image: how_to_reg.png
    content: Use our tool to find out
  - title: Frequently Asked Questions
    image: help-white.svg
    content: Learn more about OESP
  - title: Contact Us
    image: tty-white.svg
    content: | 
      Mon - Fri, 8:30 a.m. to 5:00 p.m. (ET)

      1-855-831-8151 or TTY: 1-800-855-1155
---
<style>
  @media (max-width: 640px) {
      .contain { max-width: 95%; margin: auto; }
  }
  @media (min-width: 641px) {
      .contain { max-width: 1120px; margin: auto; }
      .cols { display: flex; gap: 20px;}
  }
  .need-help { width: 100%; background-color: #F2F2F2; padding: 20px; }

.ontario-footer { margin: 0; }
.top {display: none;}
.ontario-alert { margin-bottom: 20px; }
</style>

{% include "patterns/hero.md" %}

<div class="ontario-alert ontario-alert--informational container">
    <div class="ontario-alert__header">
        <div class="ontario-alert__header-icon">
            <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet">
                <use href="#ontario-icon-alert-information"></use></svg>
        </div>
        <h2 class="ontario-alert__header-title ontario-h4">Example page alert</h2>
    </div>
    <div class="ontario-alert__body">
        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. </p>
    </div>
</div>

<div class="contain">
{% include "patterns/h-card.md" %}

## More help for more Ontarians
Effective March 1, 2024, the Ontario government has changed the household income amounts needed to qualify for OESP. This change makes more households eligible for electricity bill relief. 

Existing OESP recipients may be eligible for higher credit amounts. Please reapply to get the higher credit if you are eligible. Please contact the OESP Contact Centre at [1-855-831-8151](#) or [help@ontarioelectricitysupport.ca](#) to find out if you are eligible for a higher credit and how to reapply.

<aside class="ontario-aside">
  
  ## Beware of energy scams: {: .ontario-aside__title .ontario-h5}

  There are a growing number of scams aimed at energy consumers. The OEB and OESP are not affiliated with any private energy services companies. We do not deliver heating, cooling or any other home energy services. 

    **No** home energy assessment, audit, inspection or home visit is required to apply for the OESP.
</aside>

</div>

<div class="need-help">
<div class="contain cols">
<div class="col1">

### Need Help Applying
You can contact an intake agency for assistance. Find one close to you.
</div>
<div class="col1">
<div class="ontario-form-group">
      <label class="ontario-label" for="dropdown-list-example">
          Select a Region
      </label>
      <select class="ontario-input ontario-dropdown" id="dropdown-list-example" name="dropdown-list-example">
          <option selected value="ON">Select</option>
          <option value="option-1">Option 1</option>
          <option value="option-2">Option 2</option>
      </select>
    </div>
    <p>OR</p>
    <div style="display: flex;"><img src="/assets/imgs/google-maps.png" alt="Agency Locations in Google Maps" style="margin: 5px; height: 45px; width: auto;" ><p>Click on <a href="#">Google Maps {% include "patterns/icon-new-window.md" %}</a> link to visit Google and search using your postal code to find an intake agency in your area.</p></div>
    <p><b>There is support available to assist Indigenous communities with their applications. Indigenous households can obtain help by phone <a href="tel:18558318151">1-855-831-8151</a> or email <a href="oesp@onwaa.ca">oesp@onwaa.ca</a></b></p>
</div>
</div>
</div>

