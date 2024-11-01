---
layout: layouts/grid-container

checkbox:
  label: What is your reason for reapplying today? Please select all that are true. If none apply, please select “other” and provide your own reason.
  required: required
  list: 
    - I may be eligible or qualify for a higher credit amount under the new 2024 eligibility thresholds
    - I received a "not eligible" decision for my previous application
    - My previous application was not processed
    - My current OESP eligibility period is ending
    - I have moved or am moving
    - There are more people in my home
    - There are fewer people in my home
    - Total household income has changed (is higher)
    - Total household income has changed (is lower)
    - No longer using electricity as primary heating source
    - Now using electricity as primary heating source
    - No longer using qualified medical equipment
    - Now using qualified medical equipment
---


# Renew Application

Renew your application if you have ever applied for OESP or are currently receiving OESP credits. If you have not applied before, please return to the home page and select “New application”.

<div class="ontario-callout ontario-border-highlight--lime">

Note: Please note that if you currently receive an OESP credit, your circumstances have changed, and your application is denied, your OESP credits will stop.
</div>

<div class="ontario-form-group">
    <fieldset class="ontario-fieldset">
        <legend class="ontario-fieldset__legend">
            Have you ever submitted an application for OESP before?<span class="ontario-label__flag">(required)</span>
        </legend>
        <div class="ontario-radios">
            <div class="ontario-radios__item">
                <input class="ontario-radios__input" id="radio-button-option-1" name="radio-buttons" type="radio" value="option-1">
                <label class="ontario-label ontario-radios__label" for="radio-button-option-1">
                    Yes
                </label>
            </div>
            <div class="ontario-radios__item">
                <input class="ontario-radios__input" id="radio-button-option-2" name="radio-buttons" type="radio" value="option-2">
                <label class="ontario-label ontario-radios__label" for="radio-button-option-2">
                    No
                </label>
            </div>
        </div>
    </fieldset>
</div>

<div class="ontario-form-group">
    <fieldset class="ontario-fieldset">
        <legend class="ontario-fieldset__legend">
            Are you currently receiving an OESP credit on your electricity bill?<span class="ontario-label__flag">(required)</span>
        </legend>
        <div class="ontario-radios">
            <div class="ontario-radios__item">
                <input class="ontario-radios__input" id="radio-button-option-1" name="radio-buttons" type="radio" value="option-1">
                <label class="ontario-label ontario-radios__label" for="radio-button-option-1">
                    Yes
                </label>
            </div>
            <div class="ontario-radios__item">
                <input class="ontario-radios__input" id="radio-button-option-2" name="radio-buttons" type="radio" value="option-2">
                <label class="ontario-label ontario-radios__label" for="radio-button-option-2">
                    No
                </label>
            </div>
        </div>
    </fieldset>
</div>



{% include "patterns/checkbox.md" %}
<div class="ontario-checkboxes__item" style="top: -20px">
<input class="ontario-checkboxes__input" id="checkbox-option-1" name="options" type="checkbox" value="option-1">
<label class="ontario-checkboxes__label" for="checkbox-option-1">
<div class="ontario-form-group" style="display: flex;">
    <label style="width: 100px;" class="ontario-label" for="text-input-example">
        Other:
    </label>
    <input style="width: 400px;" class="ontario-input" type="text" id="text-input-example">
</div>
</label>
</div>

<button class="ontario-button ontario-button--primary">
    Continue
</button>