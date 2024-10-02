---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a senior researcher at the University of Oslo, associated with the [Reliable Systems group](https://www.mn.uio.no/ifi/english/research/groups/psy/index.html) 
and the [SIRIUS centre](https://sirius-labs.no), where I work on formal methods for digital twins, software engineering for and with knowledge graphs, and deductive verification.
Before I came to Oslo, I got my PhD from the Technical University of Darmstadt under the supervision of [Reiner Hähnle](https://www.informatik.tu-darmstadt.de/se/gruppenmitglieder/groupmembers_detailseite_30784.en.jsp).

My research focuses on the integration of technologies and theories from the Semantic Web with formal methods to specify, analyse and simulate data-heavy computational systems, in particular Digital Twins. I am developing and maintaining the [SMOL](https://smolang.org/) language which enables programs to use knowledge graphs for reflection and data access.
Furthermore, I research novel approaches to modularity in deductive program verification, in particular notions of contracts for distributed and hybrid systems.
I am developing and maintaining [Crowbar](https://github.com/Edkamb/crowbar-tool), a deductive verification system for Active Objects.

I am contributing to the [ABS](https://abs-models.org) language and am maintaining its variability layer and its hybrid extension [HABS](https://formbar.raillab.de/en/publications-and-tools/hybrid-abs/).

You can find a list of my publications at [dblp](https://dblp.org/pid/177/7383.html) or [Google Scholar](https://scholar.google.com/citations?user=-GBTulYAAAAJ). Preprints are published [here](/publications/), and slides of presentations [here](/talks/).

# Recent and Upcoming Events

### Awards:  International Conference on Engineering Digital Twins
Our papers at [EDTConf](https://conf.researchr.org/info/edtconf-2024/accepted-papers) got awarded the Best Paper Award and the Best Short Paper Award!
Thanks to all my co-authors and the selection committee. You find the preprints [here](/files/edtconf_1.pdf) and [here](/files/edtconf_2.pdf).

### Talk: MODELS Tutorial
I gave a tutorial on our work on semantic lifting and digital twins at MODELS'24, the slides are [here](/files/models.pdf).

### Workshop an Asynchronous Program Models
The 6th [Workshop on Asynchronous Program Models](https://edkamb.github.io/APM_24/), successor of the ABS workshop series, was be held 02. - 04.10.24 in Turin, 
and was organized by Ferruccio Damiani, Luca Paolini, Gianluca Torta, and me.

### Workshops at ISWC'24 on Software Lifecycle Management for Knowledge Graphs
I co-organize the 1st Workshop on [Software Lifecycle Management for Knowledge Graphs](https://w3id.org/soflim4kg) and the 3rd [International Workshop on Semantic Industrial Information Modelling](https://sites.google.com/view/semiim-2024)
as part of [ISWC'24](https://iswc2024.semanticweb.org)


### Talk: Lorentz Seminar 
I am glad to have participated in the Lorentz Workshop on [Contract Languages](https://www.lorentzcenter.nl/contract-languages.html).
The slides of my presentation are available [here](files/lorentz.pdf).

### Talk: Dagstuhl Seminar
I am glad to have participated in the Dagstuhl Seminar 24061 on [Are Knowledge Graphs Ready for the Real World?](https://www.dagstuhl.de/seminars/seminar-calendar/seminar-details/24061).



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

