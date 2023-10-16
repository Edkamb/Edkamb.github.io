---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral fellow at the University of Oslo, associated with the [Analytical Solutions and Reasoning group](https://www.mn.uio.no/ifi/english/research/groups/asr/index.html) 
and the [SIRIUS centre](https://sirius-labs.no), where I work on formal methods for digital twins with [Einar Broch Johnsen](https://ebjohnsen.org) and [Martin Giese](https://www.mn.uio.no/ifi/english/people/aca/martingi/). Before I came to Oslo, I got my PhD from the Technical University of Darmstadt under the supervision of [Reiner Hähnle](https://www.informatik.tu-darmstadt.de/se/gruppenmitglieder/groupmembers_detailseite_30784.en.jsp).

My research focuses on the integration of technologies and theories from the Semantic Web with formal methods to specify, analyse and simulate data-heavy computational systems, in particular Digital Twins. I am developing and maintaining the [SMOL](https://smolang.org/) language which enables programs to use knowledge graphs for reflection and data access.
Furthermore, I research novel approaches to modularity in deductive program verification, in particular notions of contracts for distributed and hybrid systems.
I am developing and maintaining the [Crowbar](https://github.com/Edkamb/crowbar-tool), a deductive verification system for Active Objects.

I am contributing to the [ABS](https://abs-models.org) language and am maintaining its variability layer and its hybrid extension [HABS](https://formbar.raillab.de/en/publications-and-tools/hybrid-abs/).

You can find a list of my publications at [dbpl](https://dblp.org/pid/177/7383.html) or [Google Scholar](https://scholar.google.com/citations?user=-GBTulYAAAAJ). Preprints are published [here](/publications/). A short version of my CV can be found [here](files/cv_short.pdf).

# Recent and Upcoming Events

### ABS Workshop'23

The 5th ABS [Workshop](https://edkamb.github.io/ABS_23/) was held in Lyon, and 
presented recent results on using [trace logics in method contracts](files/abs23_slides_1.pdf) and combining [type systems with deductive verification of distributed hybrid systems](files/abs23_slides_2.pdf).


### Presentation SPLC'23

I presented our work on [variability for functional programming](files/splc23_slides.pdf) and [SPLC'23](https://2023.splc.net/). 


### Presentation KeY Workshop'23

I presented recent results on using trace logics in method contracts at the [25th KeY Workshop](https://www.key-project.org/key-symposium/key-symposium-2023/). You can find [slides here](files/key23_slides.pdf).



### Presentation on Digital Twins for Ecological Systems

I presented an overview over our on-going activities on digital twins for ecological systems at the [Green Data Lab Conference](https://www.nmbu.no/forside/en/events/greendatalab-conference). You can find [slides](files/gdl_slides.pdf) and [abstract](files/gdl_abstract.pdf) here.


### Workshop on Applications of Formal Methods and Digital Twins

The [Workshop on Applications of Formal Methods and Digital Twins](https://fm2023.isp.uni-luebeck.de/index.php/workshop-applications-of-formal-methods-and-digital-twins/), was successfully held at [FM'23](https://fm2023.isp.uni-luebeck.de/) with 6 exciting presentations and an invited talk by Ana Cavalcanti.


### Tutorial on Semantically Reflected Digital Twins

Together with Einar Broch Johnsen, Silvia Lizeth Tapia Tarifa and Rudolf Schlatte, I gave a tutorial at [ICTAC 2022](https://viam.science.tsu.ge/clas2022/ictac/school.html) about our work on the combination of Semantic Web technologies with programming languages to enable
self-adaptive Digital Twins that react to changes in the asset model.

### Recent and Recorded Presentations
{% assign sorted = site.talks | reverse %}
  <ul>{% for post in sorted %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

# Teaching
An instance of the KalkulierbaR tool for demonstrating different proof calculi is available at [kbar.app](http://kbar.app), the source code to run an own instance is available on [github](https://github.com/kalkulierbar/kalkulierbar).

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


# Software
I develop, maintain or contribute to the following software. For details, please click on the respective tool.

  <ul>{% for post in site.portfolio %}
    {% include archive-single-mod.html %}
  {% endfor %}</ul>

