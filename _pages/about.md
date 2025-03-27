---
permalink: /
title: "About me!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello world! I’m Amedeo Pachera, a Ph.D. Student at Université Claude Bernard Lyon 1, affiliated with the LIRIS Research Lab. I am working with Prof. Angela Bonifati and Prof. Andrea Mauri.

My research lies in the integration of artificial and human intelligence to design data-intensive applications with the goal of making them efficient, effective, and aware of people's needs and values. This includes employing Human-in-the-loop techniques to enhance existing approaches in data management applications. I mainly focus on data quality tasks on graph data models, designing algorithm and user interactions to improve existing data cleaning approaches.


  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
