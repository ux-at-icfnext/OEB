---
layout: layouts/grid-container

auth: true

step:
    number: 1
    total: 4
    draft: true
    link: app2
    linkback: newapp/
    button: Continue

select:
  label: Select or Type the Utility Provider
  required: required
  list: 
    - Alectra Utilities Corporation
    - Guelph Hydro Electric Systems Inc.
    - Horizon Utilities Corporation - Alectra Utilities Corporation
---
<style>
.flex-columns { display: flex; gap: 30px;}
.full > div { width: 100%; }
.two-thirds > div:first-child {
  width: 66%;
}
img {
  cover-fit: contain;
  max-width: 90%;
}
</style>

{% include "patterns/steps.md" %}
# Utility Account Information

### Primary Utility Account Holder

<div class="flex-columns full">
<div class="ontario-form-group">
    <label class="ontario-label">
        First Name<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input two-up" type="text">
</div>
<div class="ontario-form-group">
    <label class="ontario-label">
        Last Name<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input two-up" type="text">
</div>
</div>

Note: This information is used to verify your income with Canada Revenue Agency if you are a tax filer. Please ensure the name entered is spelled exactly as it appears on your most recent tax filling. 

### Utility Account Information

Please enter your information exactly as it appears highlighted on the sample bill below. If your information is not entered as it appears as highlighted on the sample bill, your application may be returned to you for correction.

{% include "patterns/dropdown.md" %}

![alectra](/assets/imgs/alectra.jpeg)



<div class="ontario-form-group">
    <label class="ontario-label">
        Utility Account Number<span class="ontario-label__flag">(required)</span>
    </label>
    <p class="ontario-hint" id="hint-text-example-hint">Enter the information from your bill as per the highlighted instructions in the sample above </p>
    <input class="ontario-input" type="text">
</div>
<div class="ontario-form-group">
    <label class="ontario-label">
        Utility Account Holder's Full Name(s)<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>

<div class="ontario-form-group">
    <label class="ontario-label">
        Utility Account Holder’s Service Address<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>
Note: The Service Address may be different from the Mailing Address

{% include "patterns/contact.md" %}

### Mailing Address
Please enter your current address and valid postal code. Note that mailing addresses must be in Ontario.


<div class="ontario-form-group">
    <label class="ontario-label">
        Address 1 - Street Number, Name and Type<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>

<div class="flex-columns two-thirds">
<div class="ontario-form-group">
    <label class="ontario-label">
        Address 2 - Apartment, Suite or Unit Designation and Number<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>

<div class="ontario-form-group">
    <label class="ontario-label" for="text-input-example-width-20">
        Province<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input ontario-input--2-char-width" type="text" id="text-input-example-width-20">
</div>
</div>

<div class="flex-columns two-thirds">
<div class="ontario-form-group">
    <label class="ontario-label">
        City/Town<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>

<div class="ontario-form-group">
    <label class="ontario-label" for="text-input-example-width-7">
        Postal Code<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input ontario-input--7-char-width" type="text" id="text-input-example-width-20">
</div>
</div>


### Contact Information
<div class="ontario-form-group">
    <label class="ontario-label">
        Phone Number<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>
<div class="ontario-form-group">
    <label class="ontario-label">
        Email Address<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>
<div class="ontario-form-group">
    <label class="ontario-label">
        Confirm Email Address<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>


<div class="ontario-form-group" >
    <fieldset class="ontario-fieldset">
        <legend class="ontario-fieldset__legend">
            How would you like us to reach you? (required)
        </legend>
        <div class="ontario-radios">
            <div class="ontario-radios__item">
                <input class="ontario-radios__input" id="radio-button-option-1" name="radio-buttons" type="radio" value="option-1">
                <label class="ontario-label ontario-radios__label" for="radio-button-option-1">
                    Email               
                </label>
            </div>
            <div class="ontario-radios__item">
                <input class="ontario-radios__input" id="radio-button-option-2" name="radio-buttons" type="radio" value="option-2">
                <label class="ontario-label ontario-radios__label" for="radio-button-option-2">
                    Mail
                </label>
            </div>
        </div>
     </fieldset>
</div>

<div class="ontario-form-group">
    <fieldset class="ontario-fieldset">
        <div class="ontario-checkboxes">
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-1" name="options" type="checkbox" value="option-1">
                <label class="ontario-checkboxes__label" for="checkbox-option-1">
                    The Ontario Energy Board (OEB) may disclose personal information to and collect personal information from my utility provider in order to verify I am a customer.
                </label>
            </div>
        </div>
    </fieldset>
</div>


{% include "patterns/button-steps.md" %}
