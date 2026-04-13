---
permalink: /
title: "LJT - Academic Portfolio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the personal website of **LJT**, a researcher in Computer Science at the University of Example. The site is built using the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template and hosted on GitHub Pages.

## Academic Background

- **Ph.D. in Computer Science**, University of Example, 2020
- **M.Sc. in Computer Science**, University of Example, 2015
- **B.Sc. in Computer Science**, University of Example, 2012

## Research Experience

- **Postdoctoral Researcher**, University of Example, 2020–present
  - Research on machine learning, data mining, and natural language processing.
- **Graduate Research Assistant**, University of Example, 2015–2020
  - Developed scalable algorithms for large‑scale data analysis.

## Publications

Below is a list of my publications. For more details, see the [Publications](/publications/) page.

{% for pub in site.publications %}
- **{{ pub.title }}**. {{ pub.journal }}, {{ pub.year }}.
{% endfor %}

## Skills

- **Programming Languages**: Python, R, Java, C++
- **Tools & Technologies**: Git, Docker, LaTeX, Jekyll
- **Research Areas**: Machine Learning, Data Mining, Natural Language Processing

## Contact

- **Email**: ljt@example.com
- **GitHub**: [00ffcc-remove](https://github.com/00ffcc-remove)
- **Location**: Internet
- **Website**: [LJT Homepage](https://00ffcc-remove.github.io/LJT-Homepage)