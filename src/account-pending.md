---
layout: layouts/grid-container

auth: true

card:
  - title: Application
    image: description-white.svg
    link: /app
  - title: Electronic Consent Form
    image: edit_document-white.svg
  - title: Change Password
    image: manage_accounts-white.svg
  - title: Program Documents
    image: file_copy-white.svg
  - title: Frequently Asked Questions
    image: help-white.svg
  - title: Contact Us
    image: tty-white.svg
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

<div class="ontario-alert ontario-alert--informational">
    <div class="ontario-alert__header">
        <div class="ontario-alert__header-icon">
            <svg class="ontario-icon" alt="" aria-hidden="true" focusable="false" sol:category="primary" viewBox="0 0 24 24" preserveAspectRatio="xMidYMid meet"><use href="#ontario-icon-alert-information"></use></svg>
        </div>
        <h2 class="ontario-alert__header-title ontario-h4">Application Status: Pending</h2>
    </div>
    <div class="ontario-alert__body">
        <p>Your application has been submitted and is currently being processed. If you have not already done so, please complete the <a href="#">electronic consent form</a> or sign and mail a paper consent form.</p>
    </div>
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

## Privacy Note 
Your application contains personal information. Please use the “Log Off” button found at the top right of the page when you are done. If you are using a public computer, in addition to logging off, be sure to close your browser (including all tabs) to help protect your personal information.

</div>
</div>

{% include "patterns/h-card.md" %}
