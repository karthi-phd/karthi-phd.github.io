---
title: "ANTIFUNGAL COMPOUND, COMPOSITION AND USES THEREOF"
collection: patents
permalink: /patents/2023-wo2023-067625-antifungal-compound/
year: 2023

jurisdiction: "PCT"
status: "Published"
patent_office: "WIPO (PCT)"
application_number: "PCT/IN2022/050932"
publication_number: "WO2023/067625"
filing_date: 2022-10-19
publication_date: 2023-04-27

# People / orgs
inventors: "Prasanna Neelakantan; Adline Princy Solomon; Karthi Shanmugam"
assignees: "SASTRA Deemed University; Versitech Limited"

# Classifications
ipc: "A61K 31/7076; A61P 31/00; A61K 9/00"

# Links / files
pdf:
patent_link:

# National phase entries (add more countries later as needed)
national_phase:
  - country: "India"
    office: "Indian Patent Office"
    application_number: ""     # add when you have the NP number
    filing_date:
    publication_number:
    grant_number:
    status: "Designated / Pending national entry"
    link: ""                   # paste IPO link when available

# Public-safe abstract
abstract: >-
  Discloses an antifungal compound and compositions for treating fungal disease. The compound
  inhibits adhesion, biofilm formation, and filamentation at very low concentrations without
  affecting growth; embodiments include use of the FDA-approved drug Cangrelor. Methods of
  treatment and uses are provided.
---

{% include patent-meta.html inventors=page.inventors assignees=page.assignees pdf=page.pdf patent_link=page.patent_link %}

<div align="justify">

### Overview
<p>
PCT application <strong>PCT/IN2022/050932</strong> published as <strong>WO2023/067625</strong> on 27 April 2023. Applicants: SASTRA Deemed University and Versitech Limited. IPC: A61K 31/7076, A61P 31/00, A61K 9/00.
</p>

{% if page.national_phase and page.national_phase.size > 0 %}
<h3>National phase</h3>
<ul>
  {% for np in page.national_phase %}
  <li>
    {% if np.link and np.link != "" %}
      <a href="{{ np.link }}" target="_blank" rel="noopener">{{ np.country }}</a>
    {% else %}
      {{ np.country }}
    {% endif %}
    {% if np.office %} — {{ np.office }}{% endif %}
    {% if np.application_number %} • {{ np.application_number }}{% endif %}
    {% if np.status %} <em>({{ np.status }})</em>{% endif %}
  </li>
  {% endfor %}
</ul>
{% endif %}

</div>
