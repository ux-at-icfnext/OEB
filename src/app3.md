---
layout: layouts/grid-container

auth: true

step:
    number: 3
    total: 4
    draft: true
    link: app4
    linkback: app2
    button: Continue

table:
    - fname: Jane
      lname: Smith
      date: 01/01/1981
      soc: "***-***-258"
      account: Yes
      btn:
        - label: Change
    - fname: John
      lname: Smith
      date: 01/01/1980
      soc: "***-***-123"
      account: No
      btn:
        - label: Change
        - label: Remove
    - fname: Jack
      lname: Smith
      date: 01/01/2008
      soc: "***-***-987"
      account: No
      btn:
        - label: Change
        - label: Remove
    - fname: Janey
      lname: Smith
      date: 01/01/2010
      soc: "***-***-758"
      account: No
      btn:
        - label: Change
        - label: Remove
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
li {
    max-width: 80ex;
}
.large-table {
        display: none;
}
@media (min-width: 800px) {
    .content {
        display: flex;
        gap: 30px;
    }
    .content .ontario-form-group {
        width: 45%;
    }
    .small-table {
        display: none;
    }
    .large-table {
        display: block;
    }
}
</style>

{% include "patterns/steps.md" %}
# People in Your House

Please add the names and birth dates of all members living in the home for six or more months of the year, including yourself. Include the Social Insurance Number (SIN) for all household members 18 and older. 

This information is used to verify income with the Canada Revenue Agency.  Please ensure each name is spelled exactly as it appears on the most recent tax return.

Note, for privacy reasons:
1. Only the last three digits of a SIN will display once you click "Add".
2. All information for household members under 18 years of age will be deleted from the application after the eligibility decision is made.

<aside class="ontario-aside">

Only information about the applicant’s electricity account, and the amount of OESP for which the applicant’s household may be eligible, will be disclosed to the utility provider. The utility provider will not be provided with other personal information about the applicant and members of the applicant’s household, such as their SIN, income or dates of birth.
</aside>

## Household Member
Household Member heading, include only the following copy (the instructions listed here have been condensed and rewritten into the copy for the section above Household Member):

Enter a household member's information and click "Add". Then, their information will appear in the table below.

<div class="flex-columns full">
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
</div>


<div class="flex-columns full">
<div class="ontario-form-group">
    <label class="ontario-label">
        Date of Birth<span class="ontario-label__flag">(required)</span>
    </label>
    <br />
    <input class="ontario-input" type="date">
</div>

<div class="ontario-form-group">
    <label class="ontario-label">
        Social Insurance Name<span class="ontario-label__flag">(required)</span>
    </label>
    once you add, this will no longer be visible
    <input class="ontario-input" type="text">
</div>
</div>

<a href="/app3" class="ontario-button ontario-button--primary">Add</a>

{% include "partials/housetable.md" %}

<div class="ontario-form-group" style="margin-top: 20px;">
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
{% include "patterns/button-steps.md" %}