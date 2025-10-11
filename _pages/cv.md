---
layout: page
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<div class="cv-actions" style="margin-bottom:.75rem">
  <a class="btn btn--primary" href="/files/Karthi_Shanmugam_CV.pdf" target="_blank" rel="noopener">Download CV (PDF)</a>
  <button class="btn" onclick="window.print()">Print</button>
</div>

<div align="justify" markdown="1">

## Contact
**Karthi Shanmugam, Ph.D.**  
Assistant Professor, Division of Bioinformatics, School of Chemical & Biotechnology, SASTRA Deemed University  
Tiruchirapalli, Tamil Nadu, India  
Email: <karthi@scbt.sastra.edu>  
ORCID: [0000-0002-3198-4036](https://orcid.org/0000-0002-3198-4036) · Scholar: [Google Scholar](https://scholar.google.com/citations?user=EnEq7LkAAAAJ&hl=en) · ResearchGate: [Profile](https://www.researchgate.net/profile/Karthi-Shanmugam) · LinkedIn: [Profile](https://www.linkedin.com/in/kshanmugam-phd/)

## Research Summary
Computational and translational drug discovery with a focus on antibiofilm and antivirulence strategies, small-molecule design, and cardioprotective mechanisms in ischemia–reperfusion injury. Emphasis on data-driven modeling, molecular simulation, and mechanism-informed validation.

## Academic Appointments
- **Assistant Professor**, Division of Bioinformatics, SASTRA Deemed University, 2007–present  
  Supervision in antibiofilm discovery, quorum-sensing modulation, and computational drug design; 35+ UG/PG projects guided.

## Education
- **Ph.D.**, SASTRA Deemed University, 2019–2025  
  Thesis: *From Computational Discovery to Mechanistic Validation: Fisetin in Ischemia–Reperfusion Injury*
- **M.Tech (Bioinformatics)**, SASTRA Deemed University, 2005–2007  
  Thesis: *Structure-Guided Computational Design of Human Aromatase Inhibitors*
- **M.Sc. (Chemistry)**, Bharathidasan University, 2003–2005  
  Thesis: *Synthesis and Antimicrobial Activity of Mannich Bases of N-methyl piperazine*

## Research Interests
- Biofilms & AMR, quorum sensing, small molecules and natural products  
- Cardiovascular injury, mitochondrial preservation, pro-survival signaling  
- AI/ML for QSAR/ADMET, toxicity prediction, molecular design  
- Virtual screening, MD simulations, MM/GBSA, DFT

## Grants & Funding
- [Add grant title], PI/Co-PI, [Agency], [Year–Year], [one-line aim].  
- [Add grant title], PI/Co-PI, [Agency], [Year–Year], [one-line aim].

## Teaching
B.Tech: Medicinal Chemistry, Drug Design, Immunoinformatics, Applied Bioinformatics  
M.Tech: Molecular Modelling & Drug Design, Drug Informatics  
Curriculum initiatives: introduced **Drug Informatics** elective; updated **Immunoinformatics** with computational immunology & vaccine design; led hands-on modules in docking (Schrödinger, AutoDock), cheminformatics (RDKit, DeepChem), MD (GROMACS).  
Details: **[Teaching](/teaching/)**

## Supervision & Mentoring
- Ph.D.: [Student, topic, 20XX–present]  
- M.Tech/B.Tech: 35+ dissertations and projects in cheminformatics, pharmacoinformatics, antimicrobial research.

## Service & Leadership
- Reviewer: *[journal list]*  
- Committees: *[department/university committees]*  
- Organization: *[workshops/conferences]*

## Honors & Awards
- **Guru Shreshta Award (Best Teacher)**, SASTRA Deemed University, 2025  
- **Faculty Research Fellowship**, IIT Delhi (with Prof. Durai Sundar), 2009

## Invited Talks (selected)
- *[Talk title]*, [Venue/Host], [Year]  
- *[Talk title]*, [Venue/Host], [Year]

## Skills
- **Computational:** Schrödinger, AutoDock, GROMACS, Gaussian, MM/GBSA  
- **AI/ML:** Python, R, RDKit, QSAR/ADMET, DeepChem, TensorFlow  
- **Experimental:** biofilm assays, QS inhibition, antifungal/antibacterial testing, natural-product screening

---

## Publications (full list)

{% assign pubs = site.publications | sort: "date" | reverse %}

<ol class="publist">
{% for p in pubs %}
  <li class="pub">
    <div class="cit">
      {% if p.authors %}{{ p.authors }}.{% endif %}
      {% if p.title %}
        {% if p.url %}
          “<a href="{{ p.url | relative_url }}">{{ p.title }}</a>”
        {% else %}
          “{{ p.title }}”
        {% endif %}
      {% endif %}
      {% if p.venue %} <em>{{ p.venue }}</em>{% endif %}
      {% if p.date %} {{ p.date | date: "%Y" }}{% endif %}

      {%- if p.volume or p.issue or p.pages -%}
        .
        {%- if p.volume -%} {{ p.volume }}{%- endif -%}
        {%- if p.issue -%}({{ p.issue }}){%- endif -%}
        {%- if p.pages -%}: {{ p.pages }}{%- endif -%}
      {%- endif -%}.
      
      <span class="pub-links">
        {% if p.pdf %}
          <a href="{{ p.pdf | relative_url }}" target="_blank" rel="noopener" class="pub-icon">PDF</a>
        {% endif %}
        {% if p.doi %}
          <a href="{{ p.doi }}" target="_blank" rel="noopener" class="pub-icon">DOI</a>
        {% elsif p.paperurl %}
          <a href="{{ p.paperurl }}" target="_blank" rel="noopener" class="pub-icon">Link</a>
        {% endif %}
      </span>
    </div>
  </li>
{% endfor %}
</ol>

</div>

**Last updated:** {{ "now" | date: "%B %d, %Y" }}
