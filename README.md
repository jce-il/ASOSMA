---
layout: default
title: Azrieli Students On Software Modeling and Architecture -- ASOSMA 2016
overview: true
permalink: /index.html
creator: 
- role: Editor
- text: robi-y
date: July 2016, Version 1.0
---
# [ASOSMA 2016][ASOSMA.io]

**[robi-y].**<br/>
**Software Engineering Department**
**Azrieli - Jerusalem College of Engineering, Israel 2016**

[robi-y]: https://github.com/robi-y

<!--
## Table of Contents

* [Introduction](#Introduction)
* OptiKey: [OptiKey](OptiKey/)
  * [Readme](OptiKey/README.md)  
  * [Introduction](OptiKey/Introduction.md)
  * [ViewS and Prespectives](OptiKey/viewsandprespectives.md)
  * [Metrics , Variability and Quality](https://github.com/adirel/ASOSMA/blob/master/OptiKey/MetricsVariabilityQuality.md)
  * [OptiKey presentation and conclusions](https://github.com/adirel/ASOSMA/blob/master/OptiKey/ASOSNA - OptiKey.pptx)
* BeEF: [BeEF] (BeEF/)
  * [Readme](BeEF/Readme.md)
* Video.JS: [Video.JS](VideoJs/):
  * [Readme](VideoJs/README.md)
* [Firefox-ios](firefox-ios):
  * [Readme](firefox-ios/README.md)  
-->

## Introduction

Azrieli Students On Software Modeling and Architecture is a collection of modeling and architectural descriptions of open source software systems written by students from Azrieli - Jerusalem College of Engineering during a master level [course][sw-modeling-2016b] taking place in 2016.

[sw-modeling-2016b]: https://github.com/jce-il/sw-modeling-2016b

Teams of students could adopt a project of choice on GitHub. The projects selected had to be sufficiently complex and actively maintained.

Inspired by Brown and Wilsons' [Architecture of Open Source Applications][aosa], and the [DESOSA] 2015 book (update: this is a newer [desosa2016] version), each description appears as a chapter, resulting in the present online book.

[DESOSA]: http://delftswa.github.io/
[desosa2016]: https://delftswa.gitbooks.io/desosa2016/content/

## Recurring Themes

(Taken from [DESOSA], we more or less followed these themes + security views):
The chapters share several common themes, which are based on smaller assignments the students conducted as part of the course. These themes cover different architectural 'theories' as available on the web or in textbooks. The course used  Rozanski and Woods' [Software Systems Architecture][rw], and therefore several of their architectural [viewpoints] and [perspectives] recur.

[viewpoints]: http://www.viewpoints-and-perspectives.info/home/viewpoints/
[perspectives]: http://www.viewpoints-and-perspectives.info/home/perspectives/

The first theme is outward looking, focusing on the use of the system. Thus, many of the chapters contain an explicit [stakeholder analysis], as well as a description of the [context] in which the systems operate. These were based on available online documentation, as well as on an analysis of open and recently closed issues for these systems.

[context]: http://www.viewpoints-and-perspectives.info/home/viewpoints/context/
[stakeholder analysis]: http://www.mindtools.com/pages/article/newPPM_07.htm

A second theme involves the [development viewpoint][development], covering modules, layers, components, and their inter-dependencies. Furthermore, it addresses integration and testing processes used for the system under analysis.

[development]: http://www.viewpoints-and-perspectives.info/home/viewpoints/

A third recurring theme is _variability management_. Many of today's software systems are highly configurable. In such systems, different features can be enabled or disabled, at compile time or at run time. Using techniques from the field of [product line engineering][fospl], several of the chapters provide feature-based variability models of the systems under study.

A fourth theme is [metrics-based evaluation of software architectures][bouwers]. Using such metrics architects can discuss  (desired) quality attributes (performance, scaleability, maintainability, …) of a system quantitatively. Therefore various chapters discuss metrics and in some cases actual measurements tailored towards the systems under analysis.

[fospl]: http://link.springer.com/book/10.1007/978-3-642-37521-7
[bouwers]: http://repository.tudelft.nl/view/ir/uuid:6b65c5f5-398c-4a41-8806-31c638b1891c/

## First-Hand Experience

Last but not least, the chapters are also based on the student's experience in actually contributing to the systems described. As part of the course over some pull requests to the projects under study were made, e.g, bug fixes:
  [firefox-ios 1889](https://github.com/mozilla/firefox-ios/pull/1889), and contributed documentation.
  
Through these contributions the students often interacted with lead developers and architects of the systems under study, gaining first-hand experience with the architectural trade-offs made in these systems.

## Feedback

While we worked hard on the chapters to the best of our abilities, there will be plenty of omissions and inaccuracies.
We value your feedback on any of the material in the book. For your feedback, you can:

* Open an issue on our [GitHub repository for this book][ASOSMA].
* Offer an improvement to a chapter by posting a pull request on our [GitHub repository][ASOSMA].
* ~~Contact @[ASOSMA][ASOSMA.tw] on Twitter.~~
* Send an email to the lecturer (on [course][sw-modeling-2016b] syllabus).

[ASOSMA]: https://www.github.com/jce-il/ASOSMA
[ASOSMA.io]: http://jce-il.github.io/ASOSMA
[ASOSMA.tw]: https://twitter.com/ASOSMA


## Acknowledgments

We would like to thank:

* Rebecca Wirfs-Brock for course content
* AOSA and DESOSA for inspirtion


## Further Reading

1. Arie van Deursen, Alex Nederlof, and Eric Bouwers. Teaching Software Architecture: with GitHub! [avandeursen.com][teaching-swa], December 2013.
1. Nick Rozanski and Eoin Woods. [Software Systems Architecture: Working with Stakeholders Using Viewpoints and Perspectives][rw]. Addison-Wesley, 2012, 2nd edition.
1. Amy Brown and Greg Wilson (editors). [The Architecture of Open Source Applications][aosa]. Volumes 1-2, 2012.
1. Rebecca Wirfs-Brock, [Developing and Communicating Software Architecture][dcsa] Course.

[teaching-swa]: http://avandeursen.com/2013/12/30/teaching-software-architecture-with-github/
[rw]: http://www.viewpoints-and-perspectives.info/
[aosa]: http://aosabook.org/
[dcsa]: http://wirfs-brock.com/developing_comm_arch.html


## Copyright and License

The copyright of the chapters is with the authors of the chapters. All chapters are licensed under the [Creative Commons Attribution 4.0 International License][cc-by].
Reuse of the material is permitted, provided adequate attribution (such as a link to the chapter on the [book site][ASOSMA.io]) is included.


[![Creative Commons](cc-by.png)][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
