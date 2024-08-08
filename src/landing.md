---
layout: layouts/base
---
<style>
.hero { background-color: #1080A6;}

.ontario-dropdown{background-color:#fff;background-image:url("/assets/imgs/ontario-material-dropdown-arrow-48px.svg");background-position:right .5rem center;background-repeat:no-repeat;background-size:2rem;padding-right:2.25rem;cursor:pointer}.ontario-dropdown::-ms-expand{display:none}.ontario-dropdown option{font-weight:normal}

.message {
  background-image: url("/assets/imgs/hero.png");
  background-size: cover;
  padding: 2rem;
  color: #fff;
}
@media (max-width: 640px) {
  .message h1 {
    font-size: 27px;
    max-width: 95%;
  }
  .message p {
    font-size: 1.25rem;
    max-width: 95%;
  }
}
@media (min-width: 641px) {
  .message {max-width: 1120px; margin: auto;}
  .message h1 {
    font-size: 33px;
    max-width: 60%;
  }
  .message p {
    font-size: 1.25rem;
    max-width: 45%;
  }
  .information {
    max-width: 50%;
  }
  .status {
    max-width: 50%;
  }
  .section1 {
    padding: 50px;
  }
  .section1 h2 {
    padding-bottom: 1rem;
  }
  .section2 {
    background-color: #F8E5C3;
    padding: 50px;
  }
  .section2-content .col1 {
    max-width: 50%;
  }
  .section3, .section2-content {
    display: flex;
    gap: 50px;
    padding: 50px;
  }
  footer { margin-top: 0;}
}

.ontario-card__image-container { background-color: #F8E5C3; }
</style>

<div class="hero" markdown="1">
<div class="message" markdown="1">

# There’s help for lower-income households. Get help. Start now.

Welcome to the Ontario Electricity Support Program (OESP). If you are a customer of an electricity utility and in a lower-income home, you may qualify for a reduction on your electricity bill. The OESP can reduce the cost of your household electricity depending on how many people live in your home and your combined household income.

<a href="/newapp" class="ontario-button ontario-button--secondary">New Application</a><a href="/renewapp" class="ontario-button ontario-button--secondary">Renew Application</a>
</div>
</div>


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

<div class="section1 container">
  <h2>Learn more about the program</h2>
<ul class="ontario-card__container ontario-card--cards-per-row-3">
    <li class="ontario-card ontario-card--image--one-third   ontario-card--position-horizontal ontario-card--position-horizontal__image-left">
        <div class="ontario-card__image-container">
            <img class="ontario-card__image" src="/assets/imgs/faq.png" alt="card component image">
        </div>
        <div class="ontario-card__text-container ontario-card--image-true">
            <h2 class="ontario-card__heading">
                <a href="/faqs">
                    Frequently Asked Questions
                </a>
            </h2>
        </div>
    </li>
    <li class="ontario-card ontario-card--image--one-third   ontario-card--position-horizontal ontario-card--position-horizontal__image-left">
        <div class="ontario-card__image-container">
            <img class="ontario-card__image" src="/assets/imgs/paper-app.png" alt="card component image">
        </div>
        <div class="ontario-card__text-container ontario-card--image-true">
            <h2 class="ontario-card__heading">
                <a href="/forms">
                    Documents
                </a>
            </h2>
        </div>
    </li>
    <li class="ontario-card ontario-card--image--one-third   ontario-card--position-horizontal ontario-card--position-horizontal__image-left">
        <div class="ontario-card__image-container">
            <img class="ontario-card__image" src="/assets/imgs/eligible.png" alt="card component image">
        </div>
        <div class="ontario-card__text-container ontario-card--image-true">
            <h2 class="ontario-card__heading">
                <a href="/eligible">
                    Are you Eligible?
                </a>
            </h2>
        </div>
    </li>
</ul>
</div>

<div class="section2">
  <div class="section2-content container">
  <div class="col1" markdown="1"> 
    <h3>More help for more Ontarians</h3>
    Effective March 1, 2024, the Ontario government has changed the household income amounts needed to qualify for OESP. This change makes more households eligible for electricity bill relief. 

    Existing OESP recipients may be eligible for higher credit amounts. Please reapply to get the higher credit if you are eligible. Please contact the OESP Contact Centre at [1-855-831-8151](#) or [help@ontarioelectricitysupport.ca](#) to find out if you are eligible for a higher credit and how to reapply.

    <h3>Beware of energy scams:</h3>

    There are a growing number of scams aimed at energy consumers. The OEB and OESP are not affiliated with any private energy services companies. We do not deliver heating, cooling or any other home energy services. 

    **No** home energy assessment, audit, inspection or home visit is required to apply for the OESP.

  </div>
  <div class="col2">
    <h2>Check the status of your application</h2>
    <p>Your User ID and a temporary password were emailed to you when you saved or submitted your application.</p>
    <div class="ontario-form-group">
        <label class="ontario-label" for="text-input-example">
            User ID:<span class="ontario-label__flag">(required)</span>
        </label>
        <input class="ontario-input" type="text" id="text-input-example">
    </div>
    <div class="ontario-form-group">
        <label class="ontario-label" for="text-input-example">
            Password:<span class="ontario-label__flag">(required)</span>
        </label>
        <input class="ontario-input" type="text" id="text-input-example">
    </div>
    <button class="ontario-button ontario-button--secondary">Login</button>
    <p><a href="#">Forgot User ID?</a><br /> <a href="#">Forgot Password?</a></p>
  </div>
  </div>
</div>


<div class="section3 container">
  <div class="col1">
    <h3>Need help applying?</h3>
    <p>You can contact an intake agency for assistance. Find one close to you.</p>
  </div>
  <div class="col2">
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

