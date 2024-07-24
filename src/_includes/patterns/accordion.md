<style>
    .ontario-accordions__container {max-width: 100%; padding-bottom: 32px;}
    .ontario-accordions__container p {padding-bottom: 1rem;}
    .ontario-accordion-heading {max-width: 100%;}
    .ontario-accordion__button{ max-width: 100%;}
</style>

{% if accordion.alpha %}
  {% assign alpha = accordion.alpha %}
{% else %}
  {% assign alpha = "a" %}
{% endif %}

<div class='ontario-accordions__container'>
<div class='ontario-accordion__controls'>
<button class='ontario-accordion__button--expand-all' aria-expanded='false'>
<span class='ontario-accordion--expand-open-all'>Expand all</span>
<span class='ontario-accordion--expand-close-all'>Collapse all</span>
</button>
</div>
{% for acc in accordion.list %}
<div class='ontario-accordion' id='accordion-{{alpha}}-{{forloop.index}}'>
<h3 class='ontario-accordion-heading'>
<button class='ontario-accordion__button' id='accordion-button-id-{{alpha}}-{{forloop.index}}' aria-controls='accordion-content-{{alpha}}-{{forloop.index}}' aria-expanded='false' data-toggle='ontario-collapse'>
<span class='ontario-accordion__button-icon--close'>
    <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"><use href="#ontario-icon-chevron-up"></use></svg>
</span>
<span class='ontario-accordion__button-icon--open'>
    <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"><use href="#ontario-icon-chevron-down"></use></svg>
</span>{{ acc.title }}</button>
</h3>
<section class='ontario-accordion__content' id='accordion-content-{{alpha}}-{{forloop.index}}' aria-labelledby='accordion-button-id-{{alpha}}-{{forloop.index}}' aria-hidden='true' data-toggle='ontario-expander-content'>
{{ acc.content | markdownify }}
</section>
</div>
{% endfor %}
</div>