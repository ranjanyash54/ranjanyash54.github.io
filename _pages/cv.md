---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% assign cv_file = base_path | append: "/files/Resume.pdf" %}

<p class="cv-actions">
  <a class="btn" href="{{ cv_file }}" target="_blank" rel="noopener">Open in new tab</a>
  <a class="btn" href="{{ cv_file }}" download>Download PDF</a>
</p>

<object class="cv-embed" data="{{ cv_file }}" type="application/pdf" aria-label="Curriculum vitae of Yash Ranjan">
  <p class="cv-embed__fallback">
    Your browser can't display PDFs inline.
    <a href="{{ cv_file }}">Download the CV</a> instead.
  </p>
</object>
