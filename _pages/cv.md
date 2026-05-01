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
* **University of Paris Dauphine – PSL**, Master 1 Mathematics and Applications (Upcoming Sep 2026)
  * PGSM Scholarship: Prestigious merit-based scholarship granted by FSMP.
* **WorldQuant University**, MSc in Financial Engineering (April 2025 - Now)
* **Budapest University of Technology and Economics**, BSc in Mathematics, Specialization in Stochastic Processes (2022 - 2025)
  * GPA: 4.68/5.0. Valedictorian of the faculty.
  * Thesis: "The Impact of Social Media Sentiment on Cryptocurrency Markets" (Grade: 5.0/5.0).

Work Experience
======
* **FiinGroup Joint Stock Company**, Middle Credit Risk Modeling (May 2025 - Now)
  * Developed and validated credit risk models for Forward-Looking PD term structure using Survival Analysis and Markov Chain approaches.
  * Developed an AI-Driven Business Intelligence Search & Recommendation System.
* **BKK - Budapesti Közlekedési Központ**, Data Scientist Intern (Sep 2023 - Jan 2024)
  * Predicted bike sharing demand using machine learning and deep learning models.
  * Developed a traffic visualization dashboard using GeoPandas and NetworkX.

Research Experience
======
* **Vietnam Institute of Advanced Study in Mathematics**, Research Fellowship (Aug 2025 - Nov 2025)
  * Thesis: "A Modified SIS Epidemic Model with Application to Health Insurance Pricing".
* **Institute of Mathematics - VAST**, Summer Research Fellowship (April 2025 - July 2025)
  * Research on Mixing times of Markov chains.

Skills
======
* **Programming**: Python, R, C++, MATLAB, SQL, LaTeX
* **Machine Learning & AI**: TensorFlow, Keras, Scikit-learn, LangChain, LLMs, Statsmodel, Optuna
* **Data Engineering**: MySQL, SQLAlchemy, Git, GCP, Docker, Selenium, BeautifulSoup, Streamlit
* **Languages**: Vietnamese (Native), English (Professional), French (A2), Hungarian (A2)

Honors and Scholarships
======
* PGSM Scholarship, FSMP (2026)
* Erasmus Mundus Joint Master Scholarships (2026)
* Special Award at BME Student Scientific Conference (TDK) (2024)
* Stipendium Hungaricum Excellence Award (2023 & 2024)
* First Prize, Techainer AI Hackathon (2022)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<div class='cv-download-links'>
  <a href='{{ base_path }}/files/cv.pdf' class='btn btn--primary'>Download CV as PDF</a>
  <a href='{{ base_path }}/cv-json/' class='btn btn--inverse'>View JSON CV</a>
</div>
