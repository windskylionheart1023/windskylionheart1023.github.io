---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Engineering Science, KU Leuven, Belgium, 2024 – present
  * ESAT-PSI (Processing Speech and Images), supervisor: Prof. Hugo Van hamme
  * Topic: streaming automatic speech recognition
* Master of Statistics and Data Science, KU Leuven, Belgium
* Bachelor of Financial Engineering, Sichuan University, China

Research interests
======
* Streaming ASR with Conformer-based models (chunk-based attention, lookahead control)
* Confidence estimation and calibration for ASR
* Speech large language models

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Supervision
======
* Daily supervisor of Master of Artificial Intelligence thesis students, KU Leuven (2026 – 2027)

Service
======
* Reviewer, ICASSP 2027 (Speech and Language Processing)
