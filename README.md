# A Data-Driven Analysis of Accessibility in News & Media

## Team: LeadHERs

### Technology is not neutral. It either opens doors or creates barriers.

Final Website Deliverable: https://readymag.website/u1965541116/6126603/

📌 Project Overview

This project analyzes over 3,500 real-world web accessibility violations from the AccessGuru dataset. Our goal was to identify where digital systems fail users and to highlight systemic accessibility barriers within the News & Media sector.

We focused on understanding:
- Which domains have the highest accessibility violations?
- What WCAG 2.1 rules are most frequently violated?
- Why does News & Media show disproportionately high failure rates?
- What practical actions can organizations take?
This project was developed during the DubsTech Datathon.

📊 Dataset
Source: AccessGuru Dataset
- 3,500+ accessibility violations
- 448 websites
- 112 WCAG 2.1 violation types
- Domains include health, education, government, news, technology, and e-commerce
Each record includes violation type, severity score, affected HTML elements, and WCAG references.

🔎 Key Findings
- News & Media platforms recorded the highest number of accessibility violations.
- Color contrast (AA and AAA) violations were the most frequent failures.
- Duplicate IDs and structural markup errors were also common.
- Visual readability is the most significant accessibility barrier in News & Media.
These findings suggest systemic design patterns that prioritize aesthetics over accessibility.

🧠 Methodology
Our analysis followed these steps:
1. Filtered out unsuccessful scrapes.
2. Grouped violations by domain category.
3. Aggregated total violation counts per domain.
4. Identified the top three WCAG 2.1 violations within each major domain.
5. Conducted focused analysis on the News & Media sector.
6. Compared violation frequency and severity scores.
Tools used:
1. Python
2. Pandas
3. Matplotlib / Seaborn
4. Jupyter Notebook

Data-driven analysis of WCAG 2.1 accessibility violations in News &amp; Media platforms, highlighting systemic barriers and proposing actionable solutions for digital inclusion.


