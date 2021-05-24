---
title: "IRCAM Forum Workshop"
comments: true
read_time: true
header:
  teaser: assets/images/ircam_forum_th.jpg

categories:
  - research
tags:
  - workshop
  - computer-assisted composition
  - creative coding
  - notation
  - IRCAM
  - McGill University
  - Canada
---

I have been invited to give a presentation at the [IRCAM Forum Workshop][ircam_forum_workshop_2020]. Including representatives of IRCAM, the Société des arts technologiques, the Université de Montréal, the workshop will take place on April 2-5, 2020 at McGill University in Montreal, Canada. With the topic of _Spatialization, Orchestration, Perception_, the workshop is designed to investigate different aspects of musical space and timbre. I am scheduled to deliver an introduction to the creative music encoding of compositions; a brief description of my contribution is included below.

{% capture notice-2 %}

#### Code as Music: An Introduction to the Music Encoding of Compositions

The computer-assisted composition is considered both a tool in the creation and optimization of the compositional process and as a means for the generation of music notation created by a computer. The author presents an integrated approach to music computing and notation that offers a means of encoding methodology that fuses the conceptualization of _music encoding_ with the contextualization of _encoded music_. This results in an approach to computer-assisted composition that aims to combine the symbolic music information generation and retrieval process with a digital representation of the musical structure. The former is achieved by the conceptual encoding of given data structures using Abjad, a Python application programming interface that enables composers to encode musical representations and levels of musical structure incrementally (e.g., through the assemblage of basic building blocks of musical objects: pitches, chords, rhythms, meters, as well as dynamics, articulations, etc.). The latter is realized in the form of a typeset score using Lilypond, a computer program for music engraving written in C++ that is integrated with the Abjad package, which in turn enables composers to have direct control over the notation and engraving of the notational objects. This process allows for not only a more interactive encapsulation of the creative process within the environment for algorithmic composition, but it also accounts for the formation of _compositional inheritances_ of object-oriented programming. The creative potential from this approach to computer-assisted composition provides opportunities for contextual application of music encoding of musical structure as a type of formalized score control.

{% endcapture %}

<div class="notice">{{ notice-2 | markdownify }}</div>

[ircam_forum_workshop_2020]: https://www.mcgill.ca/forum2020/
