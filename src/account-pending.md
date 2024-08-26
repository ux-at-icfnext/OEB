---
layout: layouts/grid-container

auth: true

card:
  - title: Application
    image: icon-application.png
  - title: Change Password
    image: icon-settings.png
  - title: Program Documents
    image: icon-form.png
  - title: FAQs
    image: icon-question.png
  - title: Contact Us
    image: icon-contact.png
---
<style>
  img {
    width: 80px;
    height: 90px;
    object-fit: contain;
  }

  @media (min-width: 800px) {
  .content {
    display: flex;
    gap: 10%;
  }
  .content-left {
    width: 50%
  }
  .content-right {
    width: 100%
  }
  }
</style>

# Welcome, Jane Smith

This dashboard has everything you need for the Ontario Electricity Support Program (OESP). Get answers to frequently asked questions, check your application status, and monitor your account right here.

<div class="ontario-callout ontario-border-highlight--sky">
    <h2 class="ontario-callout__title ontario-h5">Application Status: Pending</h2>
    <p>Your application has been submitted and is currently being processed. If you have not already done so, please complete the <a href="#">electronic consent form</a> or sign and mail a paper consent form.</p>
</div>

<div class="content">
<div class="content-left" markdown="1">

## Application Info

**Reference Number:** OESP1700158183940515
**Utility Provider:** GUELPH HYDRO ELECTRIC SYSTEMS INC.
**Utility Account:** 1234567
**Status:** Pending
</div>

<div class="content-right" markdown="1">

{% include "patterns/h-card.md" %}
</div>