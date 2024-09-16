---
layout: layouts/grid-container

auth: true

table:
    - fname: Jane
      lname: Smith
      date: 01/01/1981
      soc: "***-***-258"
      account: Yes
    - fname: John
      lname: Smith
      date: 01/01/1980
      soc: "***-***-123"
      account: Yes
    - fname: Jack
      lname: Smith
      date: 01/01/2008
      soc: "***-***-987"
      account: No
    - fname: Janey
      lname: Smith
      date: 01/01/2010
      soc: "***-***-758"
      account: No
---
<style>
img {
  cover-fit: contain;
  max-width: 90%;
}
@media (max-width: 799px) {
    .small-table {
        display: block;
    }
    .large-table {
        display: none;
    }
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

# People in Your House
<div class="ontario-step-indicator">
    <div class="ontario-row">
        <div class="ontario-columns ontario-small-12">
            <div class="ontario-step-indicator--with-back-button">
                <button class="ontario-button ontario-button--tertiary">
                    <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet">  <use href="#ontario-icon-chevron-left"></use> </svg>Back
                </button>
                <span class="ontario-h4">Step&nbsp;3 of&nbsp;4</span>
            </div>
            <hr />
        </div>
    </div>
</div>
</div>
{% include "partials/app-nav.md" %}

<div style="padding: 30px; margin-top: 20px; " markdown="1">

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
</div>

<div class="content">
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

</div><!-- close gray box -->

---

<div style=" padding: 30px; margin-top: 20px; " markdown="1">



<div class="small-table">
<table style="width: 98%;">
<caption>Total number of household members: 4</caption>
{% for t in table %}
<tr><td>First Name</td><td>{{ t.fname }}</td></tr>
<tr><td>Last Name</td><td>{{ t.lname }}</td></tr>
<tr><td>Date of Birth</td><td>{{ t.date }}</td></tr>
<tr><td>Social Insurance Number</td><td>{{ t.soc }}</td></tr>
<tr><td>Account Holder</td><td>{{ t.account }}</td></tr>
<tr><td colspan="2" style="border-bottom: 2px #000 solid;" class="ontario-table-highlight"><a href="#" class="ontario-button ontario-button--secondary">Edit</a></td></tr>
{% endfor %}
</table>
</div>

<div class="large-table ontario-table-div">
<table>
<caption>Total number of household members: 4</caption>
<thead>
<tr>
    <th>First Name</th><th>Last Name</th><th>Date of Birth<th>Social Insurance Number</th><th>Account Holder</th><th></th>
</tr>
</thead>
{% for t in table %}
<tr>
<td>{{t.fname}}</td><td>{{t.lname}}</td><td>{{t.date}}</td><td>{{t.soc}}</td><td>{{t.account}}</td><td><a href="#" class="ontario-button ontario-button--secondary">Edit</a></td>
</tr>
{% endfor %}
</table>
</div>

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

