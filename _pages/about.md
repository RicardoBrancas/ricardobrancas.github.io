---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am a Computer Science PhD Student on the CMU Portugal Affiliated PhD Program. My advisors are [Vasco Manquinho](https://sat.inesc-id.pt/~vmm/research/index.html) at Instituto Superior Técnico, Lisboa and [Ruben Martins](https://sat-group.github.io/ruben/) at Carnegie Mellon University. My research focuses on helping programmers and non-programmes on their daily tasks, by leveraging Program Synthesis and Program Repair techniques. Some of my other research interests include Formal Methods and Compilers. Feel free to talk to me about any of these topics!

# Publications

{% for post in site.publications reversed %}
    {% include archive-single.html %}
{% endfor %}

# Projects

## ProFix

ProFix is an ongoing project that aims to help students taking classes on Logic Programming, particularly in Prolog.
In the first stage of this project we are surveying students to find the most common problems and difficulties with learning Prolog.

## FormHe

FormHe is a tool which helps users find and fix problems in ASP programs. FormHe is composed of two modules: a fault localizer module and a program repair module. The fault localizer identifies which statements of the program need to be changed/removed, based on an exemplifying query provided by the user. Then, FormHe provides the user with suggestions for how to fix the identified problems using program synthesis techniques.

## <span style="font-variant:small-caps;">Cubes</span>

CUBES is a parallel program synthesizer for the domain of SQL queries using input-output examples. CUBES extends existing sequential query synthesizers with new pruning techniques and a divide-and-conquer approach, splitting the search space into smaller independent sub-problems.