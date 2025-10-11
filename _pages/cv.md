---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV (PDF)](/files/Karthi_Shanmugam_CV.pdf)

Contact
======
* **Karthi Shanmugam, Ph.D.**
* Assistant Professor, Division of Bioinformatics, School of Chemical & Biotechnology, SASTRA Deemed University
* Tiruchirapalli, Tamil Nadu, India
* Email: karthi@scbt.sastra.edu
* ORCID: 0000-0002-3198-4036 · Google Scholar · ResearchGate · LinkedIn

Research summary
======
* Computational and translational drug discovery focusing on antibiofilm and antivirulence strategies, small-molecule design, and cardioprotective mechanisms in ischemia–reperfusion injury
* Emphasis on data-driven modeling, molecular simulation, and mechanism-informed validation

Education
======
* Ph.D., SASTRA Deemed University, 2019–2025  
  *Thesis:* From Computational Discovery to Mechanistic Validation: Fisetin in Ischemia–Reperfusion Injury
* M.Tech (Bioinformatics), SASTRA Deemed University, 2005–2007  
  *Thesis:* Structure-Guided Computational Design of Human Aromatase Inhibitors
* M.Sc. (Chemistry), Bharathidasan University, 2003–2005  
  *Thesis:* Synthesis and Antimicrobial Activity of Mannich Bases of N-methyl piperazine

Academic appointments
======
* 2007–present: Assistant Professor, Division of Bioinformatics, SASTRA Deemed University  
  * Supervise research on antibiofilm inhibitors, quorum-sensing modulators, and computational drug design  
  * Guided 35+ UG/PG projects in cheminformatics, pharmacoinformatics, and antimicrobial research

Teaching
======
* **B.Tech:** Medicinal Chemistry, Drug Design, Immunoinformatics, Applied Bioinformatics  
* **M.Tech:** Molecular Modelling & Drug Design, Drug Informatics  
* Curriculum and training: Introduced Drug Informatics elective, updated Immunoinformatics with computational immunology and vaccine design, led hands-on modules in docking (Schrödinger, AutoDock), cheminformatics (RDKit, DeepChem), and MD (GROMACS)

Skills
======
* Computational: Schrödinger, AutoDock, GROMACS, MM/GBSA, Gaussian (DFT)
* AI/ML: Python, R, RDKit, QSAR/ADMET, DeepChem, TensorFlow
* Experimental: microbial biofilm assays, quorum-sensing inhibition, antifungal/antibacterial testing, natural-product screening

Honors & awards
======
* 2025: **Guru Shreshta Award (Best Teacher Award)**, SASTRA Deemed University  
* 2009: **Faculty Research Fellowship**, IIT Delhi (with Prof. Durai Sundar)

Patents
======
* **WO2023/067625 — Antifungal compounds, compositions and uses thereof.** PCT/IN2022/050932. Filed 19 Oct 2022, Published 27 Apr 2023. Applicants: SASTRA Deemed University; Versitech Limited. Inventors: Neelakantan P; Solomon AP; **Shanmugam K**. National phase: India (2024), China (2024), United States (2025)
* **IN202241054663 — An anti-infective agent, method of treatment, and use thereof.** Filed 23 Sep 2022; Published 15 Sep 2023. Applicant: SASTRA Deemed University. Status: awaiting examination
* Full list and details: **[Patents](/patents/)**

Supervision & mentoring
======
* Ph.D.: [Student, topic, 20XX–present]  
* M.Tech/B.Tech: 35+ dissertations and projects in cheminformatics, pharmacoinformatics, antimicrobial research

Service & leadership
======
* Reviewer: *[journal list]*  
* Committees: *[department/university committees]*  
* Organization: *[workshops/conferences]*

Publications
======
<ul>
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for post in pubs %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Talks
======
<ul>
{% assign talks = site.talks | sort: "date" | reverse %}
{% for post in talks %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

Teaching items (archive)
======
<ul>
{% assign teach = site.teaching | sort: "date" | reverse %}
{% for post in teach %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
