---
layout: layouts/grid-container

auth: true

step:
    number: 2
    total: 4
    draft: true
    link: app3
    linkback: app
    button: Continue
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
.ontario-icon {
    color: rgb(0, 102, 204);
}
</style>

{% include "patterns/steps.md" %}
# Additional Information

<div style="padding: 30px; margin-top: 20px; " markdown="1">

<div class="ontario-form-group">
    <fieldset class="ontario-fieldset">
        <legend class="ontario-fieldset__legend">
            Is electric heat your primary heating source for your house? (optional)
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
            Do you, or does anyone in your house, use one of the following pieces of medical equipment at home? (optional)
        </legend>
        <div class="ontario-checkboxes">
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-1" name="options" type="checkbox" value="option-1">
                <label class="ontario-checkboxes__label" for="checkbox-option-1">
                    Mechanical Ventilator (invasive and non-invasive) <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"><use href="#ontario-icon-help"></use></svg>
                </label>
            </div>
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-2" name="options" type="checkbox" value="option-2">
                <label class="ontario-checkboxes__label" for="checkbox-option-2">
                    Oxygen Concentrator <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"><use href="#ontario-icon-help"></use></svg>
                </label>
            </div>
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-3" name="options" type="checkbox" value="option-3">
                <label class="ontario-checkboxes__label" for="checkbox-option-3">
                    Kidney Dialysis Machine <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"><use href="#ontario-icon-help"></use></svg>
                </label>
            </div>
        </div>
    </fieldset>
</div>

<div class="ontario-form-group">
    <fieldset class="ontario-fieldset">
        <legend class="ontario-fieldset__legend">
            Is any family member living in your house a member of one of the following communities? (optional)
        </legend>
        <div class="ontario-checkboxes">
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-1" name="options" type="checkbox" value="option-1">
                <label class="ontario-checkboxes__label" for="checkbox-option-1">
                    First Nations
                </label>
            </div>
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-2" name="options" type="checkbox" value="option-2">
                <label class="ontario-checkboxes__label" for="checkbox-option-2">
                    Inuit
                </label>
            </div>
            <div class="ontario-checkboxes__item">
                <input class="ontario-checkboxes__input" id="checkbox-option-3" name="options" type="checkbox" value="option-3">
                <label class="ontario-checkboxes__label" for="checkbox-option-3">
                    Métis
                </label>
            </div>
        </div>
    </fieldset>
</div>

<div class="ontario-form-group">
    <fieldset class="ontario-fieldset">
        <legend class="ontario-fieldset__legend">
            Do you or another utility account holder receive a CPP Permanent Disability pension? (optional)
        </legend>
        <div class="ontario-radios">
            <div class="ontario-radios__item">
                <input class="ontario-radios__input" id="radios-option-2" name="options" type="radio" value="option-2">
                <label class="ontario-radios__label" for="radios-option-2">
                    Yes
                </label>
            </div>
            <div class="ontario-radios__item">
                <input class="ontario-radios__input" id="radios-option-2" name="options" type="radio" value="option-2">
                <label class="ontario-radios__label" for="radios-option-2">
                    No
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
                    I verify the above information is true.
                </label>
            </div>
        </div>
    </fieldset>
</div>

</div><!-- close gray box -->


{% include "patterns/button-steps.md" %}

</div> <!-- form close -->