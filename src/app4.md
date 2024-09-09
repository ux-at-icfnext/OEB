---
layout: layouts/grid-container

auth: true
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
<div class="container">

# 4 - Review & Submit
<div class="ontario-step-indicator">
    <div class="ontario-row">
        <div class="ontario-columns ontario-small-12">
            <div class="ontario-step-indicator--with-back-button">
                <button class="ontario-button ontario-button--tertiary">
                    <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet">  <use href="#ontario-icon-chevron-left"></use> </svg>Back
                </button>
                <span class="ontario-h4">Step&nbsp;4 of&nbsp;4</span>
            </div>
            <hr />
        </div>
    </div>
</div>
{% include "partials/app-nav.md" %}

<div class="ontario-callout">
    <h4 class="ontario-callout__title ontario-h5">No missing fields</h4>
    <p>You may continue to submit your application.</p>

</div>

If you are having trouble completing your application, feel free to [email us](#).

<div class="ontario-form-group">
    <fieldset class="ontario-fieldset">
        <div class="ontario-checkboxes">
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-1" name="options" type="checkbox" value="option-1">
                <label class="ontario-checkboxes__label" for="checkbox-option-1">
                    I certify that the information I have provided on this application is true and correct.
                </label>
            </div>
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-2" name="options" type="checkbox" value="option-2">
                <label class="ontario-checkboxes__label" for="checkbox-option-2">
                    I consent to the collection, use and disclosure of my personal information by the Ontario Energy Board to determine my eligibility for the OESP and I have obtained the consent of the members of my household to provide their personal information to the Ontario Energy Board.
                </label>
            </div>
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-3" name="options" type="checkbox" value="option-3">
                <label class="ontario-checkboxes__label" for="checkbox-option-3">
                    I understand that the Ontario Energy Board may contact me in the future to learn more about my experience with the OESP.
                </label>
            </div>
        </div>
    </fieldset>
</div>

<div class="button-group">
<a href="/app3" class="ontario-button ontario-button--secondary">Previous</a>
<a href="" class="ontario-button ontario-button--primary">Submit Application</a>
</div>
</div>