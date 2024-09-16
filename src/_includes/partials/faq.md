<style>
  @media (max-width: 640px) {
  .table-large { display:none; }
  .top { display: none;}
  }
 @media (min-width: 641px) {
  .table-small { display:none; }
  .top {display: flex; justify-content: flex-end;}
   }
</style>

# Ontario Electricity Support Program

## Questions and Answers
<main id="about"></main>

### About the Program
{% include "patterns/accordion.md" %}

<div class="top">
<button onClick='scrollToTop()' id='actual-btt-button'>
    <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"> <use href="#ontario-icon-arrow-up"></use></svg><br />
    Top
</button>
</div>

<main id="amounts"></main>

### Amounts and Eligibility
{% assign accordion = amounts %}
{% include "partials/amounts.md" %}

<div class="top">
<button onClick='scrollToTop()' id='actual-btt-button'>
    <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"> <use href="#ontario-icon-arrow-up"></use></svg><br />
    Top
</button>
</div>

<main id="applications"></main>

### Applications
{% assign accordion = application %}
{% include "patterns/accordion.md" %}

<div class="top">
<button onClick='scrollToTop()' id='actual-btt-button'>
    <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"> <use href="#ontario-icon-arrow-up"></use></svg><br />
    Top
</button>
</div>

<main id="program"></main>

### Program Funding
{% assign accordion = program %}
{% include "patterns/accordion.md" %}

<div class="top">
<button onClick='scrollToTop()' id='actual-btt-button'>
    <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"> <use href="#ontario-icon-arrow-up"></use></svg><br />
    Top
</button>
</div>

<main id="other"></main>

### Other Energy Assistance Programs
{% assign accordion = other %}
{% include "patterns/accordion.md" %}

<div class="top">
<button onClick='scrollToTop()' id='actual-btt-button'>
    <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"> <use href="#ontario-icon-arrow-up"></use></svg><br />
    Top
</button>
</div>


<script src='../../scripts/back-to-top.js'></script>