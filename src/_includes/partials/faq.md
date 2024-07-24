<style>
  @media (max-width: 640px) {
  .table-large { display:none; }
  }
 @media (min-width: 641px) {
  .table-small { display:none; }
  }
</style>

# Ontario Electricity Support Program

## Questions and Answers

<main id="about"></main>

### About The Ontario Electricity Support Program
{% include "patterns/accordion.md" %}

<main id="amounts"></main>

### OESP Amounts And Eligibility
{% assign accordion = amounts %}
{% include "partials/amounts.md" %}

<main id="applications"></main>

### Applications
{% assign accordion = application %}
{% include "patterns/accordion.md" %}

<main id="program"></main>

### Program Funding
{% assign accordion = program %}
{% include "patterns/accordion.md" %}

<main id="other"></main>

### Other Energy Assistance Programs
{% assign accordion = other %}
{% include "patterns/accordion.md" %}