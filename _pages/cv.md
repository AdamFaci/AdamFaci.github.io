---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

PhD in Artificial Intelligence. Interdisciplinary researcher working at the intersection of AI and the social sciences and humanities, on knowledge graphs and large language models.

Education
======
* **Ph.D. in Artificial Intelligence**, LIP6, Sorbonne Université, Paris, 2019–2022
  * *Representation, Simulation and Mining of Knowledge in the Conceptual Graph Formalism*
  * Jury: Jean-Gabriel Ganascia, Cyril de Runz, Trevor Martin, Maria Rifqi, Marie-Jeanne Lesot, Claire Laudy. Degree awarded unanimously.
* **Engineering degree in Computer Science**, TELECOM Nancy, Villers-lès-Nancy, 2015–2018
  * Major in software engineering; artificial intelligence, software development, project management.

Positions
======
* **Oct. 2023 – Mar. 2027: Postdoctoral researcher — large language models for the SSH**
  * CNRS, Huma-Num / HN Lab, Paris
  * Interdisciplinary research and research administration within a CNRS *infrastructure de recherche étoile* (IR\*).
  * Lead of a use case on an AI research-assistant agent for the social sciences and humanities within the European project LLMs4EU.

* **Apr. – Sep. 2023: Postdoctoral researcher — ontologies for cybersecurity**
  * CNAM, Paris
  * Operationalisation of ontologies for incident response; co-supervision of a doctoral student.

Research areas
======
* Retrieval-augmented generation, scholarly agents and neuro-symbolic plans
* Knowledge graphs, conceptual graphs, ontologies and graph pattern mining
* Computer vision for art history and photojournalism (SAM2, DINO, YOLO)
* Evaluation, benchmarking and bias in generative language models
* Epistemology and socio-history of AI methods in the humanities

Publications
======
  <ul>{% assign cv_pubs = site.publications | where_exp: "post", "post.status == nil" | sort: "date" | reverse %}{% for post in cv_pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Under review and in preparation
======
  <ul>{% assign cv_pending = site.publications | where_exp: "post", "post.status" | sort: "date" | reverse %}{% for post in cv_pending %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* **Research administration.** Preparation of ANR, Labcom and European calls with Stéphane Pouyllau and Léa Maronet: formalisation of the research strategy and mobilisation of partners.
* **Doctoral co-supervision (2024–2025).** Ontology for cybersecurity incident response, doctoral work of Rayan Kanawati, with Nadira Lammari and Nada Mimouni (CNAM).
* **Co-director of a PictorIA working group** on image annotation standards in SSH, with Emmanuel Château-Dutier, Léa Maronet and Alice Truc, since November 2024.
* **Co-organiser of the seminar *Interprétations artificielles*** with Julien Schuh (participant 2025, co-organiser 2026); edited volume in preparation.
* **Session chair**, "Projets et méthodes pour la récupération et structuration de corpus", third Médias 19 congress, 2026.
* **Coordinator of an inter-doctoral working group**, THALES, Palaiseau, 2019–2021.

Doctoral defence report
======
*Jury: J.-G. Ganascia, C. de Runz, T. Martin, M.-J. Lesot, C. Laudy.*

The jury noted that the thesis is structured around three new contributions aimed at extracting frequent conceptual graph patterns and at validating that extraction. The first — whose originality the jury underlined — extracts frequent conceptual graph patterns using symbolic information fusion operators and their specific properties. The second generates synthetic conceptual graph databases, used in the thesis to validate the pattern extraction. The third is a critical review of the introduction of fuzzy modalities into conceptual graphs, with a view to mining frequent fuzzy conceptual graph patterns. The degree of *docteur en informatique* of Sorbonne Université was awarded unanimously.
