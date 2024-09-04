---
layout: layouts/grid-container

auth: true

card:
  - title: Application
    image: description.png
    link: /app
  - title: Change Password
    image: edit_document.png
  - title: Program Documents
    image: file_copy.png
  - title: FAQs
    image: ontario-icon-help.png

---
<style>
  img {
    width: 100%;
    height: auto;
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
    <h2 class="ontario-callout__title ontario-h5">Application Status: Draft</h2>
    <p>Your application has been saved but not submitted. Please <a href="#">return to your application to continue</a>.</p>
</div>

<div class="content">
<div class="content-left" markdown="1">

## Application Info

**Reference Number:** OESP1700158183940515
**Utility Provider:** GUELPH HYDRO ELECTRIC SYSTEMS INC.
**Utility Account:** 1234567
**Status:** Draft
</div>

<div class="content-right" markdown="1">

{% include "patterns/h-card.md" %}
</div>