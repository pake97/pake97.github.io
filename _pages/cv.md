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
* Ph.D in Human Machine Intelligence Integration for data-intensive applictions, Université Claude Bernard Lyon 1,  2023 - Present.
* M.S. in Computer Science and Engineering, Politecnico di Milano, 2022
* B.S. in Computer Science, Università di Padova, 2019

Work experience
======
  * Oct. 2023 - Current: Ph.D. Student
    * Université Claude Bernard Lyon 1
    * Supervisors: Prof. Angela Bonifati, Prof. Andrea Mauri

* Jun. 2022 - Oct. 2023: CTO
  * Focal SRL
  * Duties included: I was the leader of the developing team of Focal, an italian startup.  We developed a web platform for consultants (lawyers, accountants, project managers, …) based on a search engine that leverages semantic search with vector indices. The platform allows users to find the best consultant among different niches by prompting a specific need. We built the platform using the NextJS framework, integrating Zilliz as the vector database and AWS S3 for storage. We also took part in several joint projects with the John Lab (https://johnbosco.it/), a laboratory that aims to help students from high schools and universities to develop their ideas and teach them entrepreneurship skills.

* June 2022 - Sept. 2023: Research Fellow
  * Politecnico di Milano
  * Duties included: developing Data Science and Knowledge Engineering techniques for the extraction and enrichment of textual content for the analysis of the impact of the COVID-19 pandemic. The Periscope project has received funding from the European Union’s Horizon 2020 Research and Innovation programme (https://periscopeproject.eu/). I was part of the team in charge of  developing Perseus Platform (https://perseus-platform.eu/), an integrated toolkit for participatory and strategic decision-making at the EU level.  
  * Supervisor: Prof. Marco Brambilla
  
Skills
======
* Graph Databases
* Machine Learning
* Deep Learning
* Knowlegde Graphs
* Semantic Web

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>  -->

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* I had the privilege of being a member of the ARI (Availability & Reproducibility Initiative) commission at ACM SIGMOD 2024 
* PC member for the CHI workshop EmpatiCH 
* PC member for ICWE 2025
* Reviewer for TKDE (IEEE Transactions on Knowledge and Data Engineering) journal.