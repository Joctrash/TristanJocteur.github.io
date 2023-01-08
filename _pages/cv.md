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
* Licence Sciences de la Matière, Majeure Physique, Ecole Normale Superieure de Lyon (FR), 2019
* Agrégation de Physique-Chimie option Physique (classé 3ème)
* Master Physique, concepts et applications, Ecole Normale Superieur de Lyon (FR), 2022
* Thèse de doctorat en physique statistique, Universite Grenoble Alpes (FR), 2025 (supposé)

Work experience
======
* 02-07 2022: Stage de recherche
  * Laboratoire de Physique Théorique (Toulouse, France)
  * Renormalisation des paramètres élastiques d'une membrane à deux composants

* 05-07 2020: Stage de recherche
  * Centre de Physique Théorique (Marseille, France)
  * Théorie des champs actifs : relier les descriptions de Langevin et Fokker-Planck

* 06-07 2019: Stage de recherche
  * Laboratoire de Physique de l'ENS de Lyon (Lyon, France)
  * Translocation d'ADN simple brin à travers des nanopores
  
Skills
======
* Python, C++
* Parallel computing (CUDA)
* Langues
  * Français (langue maternelle)
  * Anglais (C1)
  * Russe (B1)

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
