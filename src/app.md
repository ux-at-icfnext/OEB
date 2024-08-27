---
layout: layouts/grid-container

select:
  label: Select or Type the Utility Provider
  required: required
  list: 
    - Alectra Utilities Corporation
    - Guelph Hydro Electric Systems Inc.
    - Horizon Utilities Corporation - Alectra Utilities Corporation
---
<style>
img {
  cover-fit: contain;
  max-width: 90%;
}
.content {
  display: flex;
  gap: 30px;
}
.two-thirds > div:first-child {
  width: 66%;

}
.two-up.ontario-input {
  margin: 0;
}
h3 {
  margin-bottom: 1rem;
}
h4 {
  margin-top: 1rem;
}

.save:after{
   content: 'Save Draft';
   display: block;
}
.save:focus:after,
.save:active:after{
   content: 'Draft Saved!';
   display: block;
}
</style>

# Do you have your electricity bill with you?

You’ll need it for the section below. Overall, it should take you less than 20 minutes to complete your application.

Also, please keep in mind that you will have to print out your consent form or sign electronically once the application is submitted.

## Privacy Note
Your application contains sensitive personal information. Please make sure you use the "Log Off" button found on the top right of the website when you are done.

If you are using a public computer, in addition to logging off, be sure to close your browser to help protect your personal information:

1. For Windows users, please close using the “X” button on the top right of the browser and make sure all tabs are closed.

2. For Mac users, please ensure the browser is closed by selecting the browser menu (Safari, Chrome, Firefox, etc.) from the top left of your screen and selecting Quit.

For more information on the OESP security and privacy policies go to [Program Documents](#).

## Utility Account Information

<div class="ontario-step-indicator">
    <div class="ontario-row">
        <div class="ontario-columns ontario-small-12">
            <div class="ontario-step-indicator--without-back-button">
                <span class="ontario-h4">Step&nbsp;1 of&nbsp;4</span>
            </div>
            <hr />
        </div>
    </div>
</div>

<div style="background-color: #F2F2F2; border-radius: 8px; padding: 30px; margin-top: 20px; " markdown="1">

### Primary Utitlity Account Holder

<div class="content">
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
*NOTE: This information is used to verify your income with Canada Revenue Agency if you are a tax filer. Please ensure the name entered is spelled exactly as it appears on your most recent tax filling.

#### Utility Account Information

Please enter your information exactly as it appears highlighted on the sample bill below. If your information is not entered as it appears as highlighted on the sample bill, your application may be returned to you for correction.

{% include "patterns/dropdown.md" %}

![alectra](/assets/imgs/alectra.jpeg)
*Use the image above to locate your account information*

<div class="ontario-form-group">
    <label class="ontario-label">
        Utility Account Number<span class="ontario-label__flag">(required)</span>
    </label>
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
*Please note: The Service Address may be different from the Mailing Address

If you need assistance finding information on your utility bill, please contact the OESP Contact Centre at [1-855-831-8151](/)


#### Mailing Address
_Please enter your current address and valid postal code. Note that mailing addresses must be in Ontario._

<div class="ontario-form-group">
    <label class="ontario-label">
        Address 1 - Street Number, Name and Type<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>

<div class="content two-thirds">
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
    <input class="ontario-input ontario-input--20-char-width" type="text" id="text-input-example-width-20">
</div>
</div>

<div class="content two-thirds">
<div class="ontario-form-group">
    <label class="ontario-label">
        City/Town<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>

<div class="ontario-form-group">
    <label class="ontario-label" for="text-input-example-width-20">
        Postal Code<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input ontario-input--20-char-width" type="text" id="text-input-example-width-20">
</div>
</div>


#### Contact Information
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
            How would you like us to reach you?
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

<div class="button-group">
<a href="" class="ontario-button ontario-button--secondary">Previous</a>
<a href="/app2" class="ontario-button ontario-button--primary">Next</a>
<a href="" class="ontario-button ontario-button--tertiary">Save Draft</a>
</div>

</div> <!-- closes form field -->


