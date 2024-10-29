---
layout: layouts/grid-container

auth: true

step:
    number: 4
    total: 4
    link: app2
    linkback: app3
    button: Submit application
---

{% include "patterns/steps.md" %}
# Review and Submit

<div class="ontario-alert ontario-alert--success">
    <div class="ontario-alert__header">
        <div class="ontario-alert__header-icon">
            <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"><use href="#ontario-icon-alert-success"></use></svg>
        </div>
        <h2 class="ontario-alert__header-title ontario-h4">No missing fields</h2>
    </div>
    <div class="ontario-alert__body">
        <p>You may continue to submit your application.</p>
    </div>
</div>

{% include "patterns/contact.md" %}

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



{% include "patterns/button-steps.md" %}