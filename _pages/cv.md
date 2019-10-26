---
layout: single
title: "Curriculum Vitae"
header:
  overlay_image: /assets/headers/trees.jpg
  caption: "Photo by [**Samuel Ferrara**](https://unsplash.com/@samferrara) on [**Unsplash**](https://unsplash.com/photos/iecJiKe_RNg)"
permalink: /cv/
sidebar:
  - image: "/assets/icons/avatar.jpg"
    image_alt: "Nithiya Streethran"
  - nav: "cv_nav"
redirect_from:
  - /resume
date: "2019-10-12"
comments: true
---

{% include base_path %}
{% assign author = page.author | default: page.authors[0] | default: site.author %}
{% assign author = site.data.authors[author] | default: author %}

# Nithiya Streethran

<!-- social icons and location -->

<div itemscope itemtype="https://schema.org/Person">
  <div class="author__urls-wrapper">
    <ul class="author__urls social-icons">
      {% if author.location %}
        <span style="font-size:larger">
          <li itemprop="homeLocation" itemscope itemtype="https://schema.org/Place">
            <i class="fas fa-fw fa-map-marker-alt" aria-hidden="true"></i> <span itemprop="name">{{ author.location }}</span>
          </li>
        </span>
      {% endif %}
      {% include author-profile-custom-links.html %}
    </ul>
  </div>
</div>

<div class="page__footer-follow">
  <ul class="social-icons">
    {% if site.footer.links %}
      {% for link in site.footer.links %}
        {% if link.label and link.url %}
          <span style="font-size:larger">
            <li><a title="{{ link.label }}" href="{{ link.url }}" rel="nofollow noopener noreferrer"><i class="{{ link.icon | default: 'fas fa-link' }}" aria-hidden="true"></i> </a></li>
          </span>
        {% endif %}
      {% endfor %}
    {% endif %}
  </ul>
</div>

<!-- end -->

# Experience

* *Apr 2018 - present*: Research Fellow, [**University of Stavanger**](https://www.uis.no/)
  * Marie Skłodowska-Curie Early-Stage Researcher within the [ENSYSTRA (ENergy SYStems in TRAnsition)](https://ensystra.eu/) Innovative Training Network
  * Project: ["Development of a real-time optimisation solution for dispatchable energy supply units"](https://github.com/ENSYSTRA/short-term-forecasting)
* *May 2017 - Aug 2017*: Master's Dissertation Student, [**Natural Power Consultants**](https://www.naturalpower.com/)
  * MSc dissertation: ["Specification of 'normal' wind turbine operating behaviour for rapid anomaly detection: through the use of machine learning algorithms"](https://github.com/nmstreethran/WindTurbineClassification)

# Education

* *Sep 2016 - Aug 2017*: MSc, Renewable Energy Engineering, [**Heriot-Watt University**](https://www.hw.ac.uk/)
* *Sep 2013 - May 2016*: BEng, Mechanical and Energy Engineering, [**Heriot-Watt University**](https://www.hw.ac.uk/)

# Skills

* **Programming:** Python (inc. Pandas, Numpy, scikit-learn), Git, Matlab
* **Office and typesetting:** LaTeX, Office suite of applications, HTML, CSS, Markdown
* **Operating systems:** Microsoft Windows, Linux
* **Visualisation:** Matplotlib, Google Charts, Ti*k*Z & PGF
* **Competencies:** Interdisciplinary collaboration, teamwork, project management
* **Languages:** *Proficient*: English, Malay; *Intermediate*: Tamil; *Beginner*: Norwegian (Bokmål)

# Certificates

* *Jul 2019*: Energy Law, Policy, Planning and Governance, [University of Groningen](https://www.rug.nl/)
* *May 2019*: Module 5: Open Research Software and Open Source, [Open Science MOOC](https://opensciencemooc.eu/) on Eliademy
* *Apr 2019*: Module 1: Open Principles, [Open Science MOOC](https://opensciencemooc.eu/) on Eliademy
* *Feb 2019*: Mathematics for Machine Learning, a 3-course specialisation, [Imperial College London](http://www.imperial.ac.uk/) on Coursera
* *Jan 2019*: Workshop on Energy Economics: Markets, Investment and Business, [University of Edinburgh](https://www.ed.ac.uk/)
* *Sep 2018*: Summer School on Modelling Energy Systems - Setting the Interdisciplinary Stage, [University of Flensburg](https://www.uni-flensburg.de/en/)
* *Apr 2018*: Workshop on Introduction to Energy Systems in Transition in the North Sea Region, [University of Groningen](https://www.rug.nl/)
* *Sep 2017*: Blue Growth Summer School, [Ghent University](https://www.ugent.be/)

# Memberships

* *Aug 2018 - present*: Member, [Marie Curie Alumni Association](https://www.mariecuriealumni.eu/)
* *Jun 2018 - present*: Member, [Norwegian Association of Researchers](https://www.forskerforbundet.no/english/)
* *Sep 2017 - present*: Associate Member, [Institution of Mechanical Engineers](http://www.imeche.org/)

# Interests

* **Professional:** Energy system analysis, data science for energy applications, renewable energy grid integration, open source and open science practices
* **General:** Sustainability, walking, technology, animal welfare, gardening, role-playing games
