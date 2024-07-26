---
layout: layouts/base
---
<style>
.hero { background-color: #1080A6;}

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
  .message {max-width: 1168px; margin: auto;}
  .message h1 {
    font-size: 33px;
    max-width: 65%;
  }
  .message p {
    font-size: 1.25rem;
    max-width: 60%;
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
  .section3 {
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

<button class="ontario-button ontario-button--secondary">New Application</button><button class="ontario-button ontario-button--secondary">Renew Application</button>
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
                <a href="#">
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
                <a href="#">
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
                <a href="#">
                    Are you Eligible?
                </a>
            </h2>
        </div>
    </li>
</ul>
</div>

<div class="section2">
  <div class="section2-content container">
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

