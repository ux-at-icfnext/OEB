---
layout: layouts/grid-container
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

# 3 - People in Your House
<div class="ontario-step-indicator">
    <div class="ontario-row">
        <div class="ontario-columns ontario-small-12">
            <div class="ontario-step-indicator">
                <span class="ontario-h4">Step&nbsp;3 of&nbsp;4</span>
            </div>
            <hr />
        </div>
    </div>
</div>

<div style="background-color: #F2F2F2; border-radius: 8px; padding: 30px; margin-top: 20px; " markdown="1">

## Important
Please add the name, date of birth and SIN for yourself and all household members 18 and older. The names should be entered exactly as they appear on their tax filings.

Only information about the applicant’s electricity account, and the amount of OESP for which the applicant’s household may be eligible, will be disclosed to the utility provider. The utility provider will not be provided with other personal information about the applicant and members of the applicant’s household, such as their SIN, income or dates of birth.

## Household Member
This information is used to verify your income with the Canada Revenue Agency.
1. INCLUDE ALL PEOPLE LIVING AT THE HOUSE FOR 6 OR MORE MONTHS OF THE YEAR.
2. INCLUDE NAMES AND INFORMATION OF ALL HOUSEHOLD MEMBERS THAT HAVE BEEN ADDED.
3. IF A HOUSEHOLD MEMBER IS YOUNGER THAN 18, WE DO NOT NEED A SIN.
4. FOR PRIVACY REASONS, ALL INFORMATION FOR HOUSEHOLD MEMBERS UNDER 18 WILL BE DELETED FROM THE APPLICATION AFTER THE ELIGIBILITY DECISION IS MADE.

 Please ensure the spelling is exactly as it appears in your most recent tax return.

<div class="content">
<div class="ontario-form-group">
    <label class="ontario-label">
        First Name<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>

<div class="ontario-form-group">
    <label class="ontario-label">
        Last Name<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="text">
</div>
<div class="ontario-form-group">
    <label class="ontario-label" for="text-input-example">
        Date of Birth<span class="ontario-label__flag">(required)</span>
    </label>
    <input class="ontario-input" type="date" id="text-input-example">
</div>
</div>

<div class="ontario-form-group">
    <label class="ontario-label">
        Social Insurance Number<span class="ontario-label__flag">(required)</span>
    </label>
    once you add, this will no longer be visible
    <input class="ontario-input ontario-input--20-char-width" type="text" inputmode="numeric" pattern="[0-9]" >
</div>
<a href="/app3" class="ontario-button ontario-button--primary">Add</a>

</div><!-- close gray box -->

---

<div style="background-color: #F2F2F2; border-radius: 8px; padding: 30px; margin-top: 20px; " markdown="1">

Total number of household members: 4

( TODO -- LIST HERE)
</div><!-- close gray box -->

<div style="padding: 30px; margin-top: 20px; " markdown="1">
<div class="ontario-form-group">
    <fieldset class="ontario-fieldset">
        <div class="ontario-checkboxes">
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-1" name="options" type="checkbox" value="option-1">
                <label class="ontario-checkboxes__label" for="checkbox-option-1">
                   I give consent to the Ontario Energy Board (OEB) to communicate or share the information within my OESP application, on my behalf, with the Ministry of Finance. In addition, I give consent to my Ministry of Finance to communicate with the OEB.
                </label>
            </div>
        </div>
    </fieldset>
</div>

<div class="button-group">
<a href="/app2" class="ontario-button ontario-button--secondary">Previous</a>
<a href="/app4" class="ontario-button ontario-button--primary">Next</a>
<a href="" class="ontario-button ontario-button--tertiary">Save Draft</a>
</div>

</div>

