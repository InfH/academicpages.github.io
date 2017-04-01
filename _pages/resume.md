---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /cv
---

{% include base_path %}

Education
======
* PhD in Molecular & Cell Biology, University of California, Berkeley, *2012 - present*
* AB in Molecular Biology & Certificate in Neuroscience (Quantitative & Computational Neuroscience honors track), Princeton University, *2008 - 2012*

Experience
======
* Graduate Student Researcher (UC Berkeley, Advisor: John Ngai, May 2013 – present)
Deconstructing lineage trajectories arising from olfactory stem cells at single cell resolution.
  *	Investigating how basal stem cells of olfactory epithelium contribute to steady-state neurogenesis and injury-induced regeneration using single-cell RNA-sequencing.
  *	Using clustering and lineage trajectory prediction algorithms, developed in collaboration with biostatisticians, to model cell state transitions and cell fate trajectories. 
  *	Interpreting models to form hypotheses about regulators of biological processes, which are then tested experimentally by our team.
  *	One co-first author manuscript under review; one co-first author manuscript in progress.

  * California Institute for Regenerative Medicine (CIRM) Predoctoral Fellow (January 2015 - December 2015)
  * Elizabeth Einstein Roboz Fellowship (Spring 2015)

* Career Development Initiative in the Physical Sciences Data Science Workshop (UC Berkeley, July 2016)
  *	Developed topic ontology for English Wikipedia articles and classifier for new articles.
  *	Repository available at github.com/diyadas/Topic-Ontology
* Undergraduate Researcher (Princeton University, Advisor: Sam Wang, June 2009 – June 2012)
  * Culminated in award-winning senior thesis: A Quantitative Analysis of Temperament and Connections to Neuroanatomy in the Domestic Dog (Canis familiaris).
  
Skills
====== 
* Knowledge: Data analysis, statistics, molecular biology, developmental biology, stem cell biology, neuroscience, single-cell RNA-sequencing; logistics (event organization)
* Tools: R/RStudio, Python, MATLAB, Git, some bash, molecular biology lab techniques (fluorescence-activated cell sorting, in situ hybridization), Adobe Illustrator, InDesign

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Leadership
======
  <ul>{% for post in site.portfolio %}
    {% include archive-single.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>