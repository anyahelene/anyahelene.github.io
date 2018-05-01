---
layout: "paper"
approved: "publish"
date: "2015-04-01"
bibkind: "InProceedings"
author: [ anya, ralf, vadim, Foo Bar ]
title: "Reflections on Courses for Software Language Engineering"
event: "MODELS 2014 Educators Symposium"
eventkind: "Symposium"
eventurl: "http://models2014.webs.upv.es/educationsymposium.htm"
eventyear: "2014"
eventmonth: "September"
venue: "{{ Booktitle }}, {{ Location }}"
note: 
pdfinfo: "(preprint)"
location: "Valencia, Spain"
journal: 
editor: "Birgit Demuth and Dave Stikkolorum"
publisher: "CEUR"
year: "2015"
month: "April"
address: 
volume: "1346"
issue: 
pages: "54–63"
issn: "1613-0073"
isbn:
doi: 
kind: "workshop"
category: "education, sle"
project: 
copyright: " AuthorCopyright "
---
{% capture page['Booktitle'] %}Proceedings of the {{ page.Event }}{% endcapture %}
{{ page['Booktitle']  }}
{{ site.authors.anya.name }}, {{ site.ralf }}, {{ site.vadim }} Software Language Engineering (SLE) has emerged as a field in computer science research and software engineering, but it has yet to become entrenched as part of the standard curriculum at universities. Many places have a compiler construction (CC) course and a programming languages (PL) course, but these are not aimed at training students in typical SLE matters such as DSL design and implementation, language workbenches, generalised parsers, and meta-tools.

We describe our experiences with developing and teaching software language engineering courses at the Universities of Bergen and Koblenz-Landau. We reflect on lecture topics, assignments, development of course material, and other aspects and variation points in course design.

