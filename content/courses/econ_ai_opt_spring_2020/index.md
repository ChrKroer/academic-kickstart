---
title: Economics, AI, and Optimization

summary: PhD class on how AI and optimization enables large-scale economic solution concepts.

# Schedule page publish date (NOT talk date).
publishDate: "2019-12-03T00:00:00Z"
date: "2020-01-21T13:00:00Z"
date_end: "2020-05-01T15:00:00Z"

semester: "Spring"
year: "2020"

authors: []
tags: []

# Is this a featured course? (true/false)
featured: false


# Enable math on this page?
math: true
---

### Course Info

* *Instructor:* [ Christian Kroer ](http://www.christiankroer.com)
* *Time:* Mondays & Wednesdays 1:10-2:25pm
* *Location:* 233 Mudd
* *Office hours:* Wednesday 2:25-3:30pm (or anytime; but email me first in that case)

### Course Summary
Economics, AI, and Optimization is an interdisciplinary course that will cover selected topics at the intersection of economics, operations research, and computer science. A recurring theme in the course will be how economic solution concepts are enabled at scale via AI and optimization methods. We will describe several successful practical applications, including how to:

* Make a poker AI
* Fairly allocate course seats to students, food to food banks, etc
* Protect wildlife, airports, or the power grid
* Conduct large-scale auctions for spectrum or Internet ads


### Outline
A rough outline is as follows:

* Intro to game theory and market design
* Nash equilibrium
  * Zero-sum games, minimax theorem
  * First-order methods/Online convex optimization/regret minimization in games
  * Deep learning for solving games at scale
  *	How the above is used in making superhuman poker AIs
* Security games
  * Stackelberg equilibrium
  * Basic Stackelberg security game model
  * Mixed-integer programming, deep learning for scaling up
  * Applications to airport, wildlife, power grid security
* Market design
  * Fisher markets and market equilibrium
  * Optimization methods for computing market equilibria
  * Machine learning methods for large markets
  * fair division, course allocation, 
  * Internet ad auctions
  * Spectrum auctions

We will also cover some subset of the following:

* Matching markets
* Data science in multiagent systems

### Textbooks

The primary book is:

* [ Algorithmic Game Theory (AGT) ](/files/algorithmic-game-theory.pdf)  by Nisan, Roughgarden, Tardos, and Vazirani (it's free)

Additionally, we may use some sections of the following books. They are also recommended for supplementary reading:

* [ Handbook of Computational Social Choice (HCSC) ](http://www.cambridge.org/download_file/898428) by Brandt, Conitzer, Endriss, Lang, & Procaccia (it's free, password: cam1CSC)
* [ Multiagent Systems (MS) ](http://www.masfoundations.org/download.html) by Leyton-Brown & Shoham (it's free)
* [Twenty Lectures on Algorithmic Game Theory (TLAGT)](https://www.cambridge.org/us/academic/subjects/computer-science/algorithmics-complexity-computer-algebra-and-computational-g/twenty-lectures-algorithmic-game-theory?format=PB) by Tim Roughgarden (the individual notes can be found on [Tim's website](http://timroughgarden.org/notes.html) under the course "Algorithmic Game Theory")

### Tentative schedule
| #  | <div style="width:45px">Date</div> | Topic | Reading | Lecturer |
|---|--------|----------|---|---|
| 1 | 1 / 22 | Introduction | AGT Ch 1 | Kroer |
| 2 | 1 / 27 | Introduction to game theory | AGT Ch 2 | Kroer |
| 3 | 1 / 29 | Online convex optimization, minimax theorem | | Kroer |
| 4 | 2 / 3 | Blackwell approachability, regret matching  | | Kroer |
| 5 | 2 / 5 | Extensive-form games, sequence form LP | AGT Ch 3.7 - 3.11 | Kroer |
| 6 | 2 / 10 | EFG regret decomposition, CFR+ | | Kroer |
| 7 | 2 / 12 | Subgame solving, DeepStack | | Kroer |
| 8 | 2 / 17 |  |  | Kroer |
| 9 | 2 / 19 | Security games | | Kroer |
| 10 | 2 / 24 | Green Security games | | Kroer |
| 11 | 2 / 26 | Introduction to mechanism design | AGT Ch 2 | Kroer |
| 12 | 3 / 2 | Introduction to mechanism design 2 | AGT Ch 2 | Kroer |
| 13 | 3 / 4 | Market equilibrium, Eisenberg-Gale convex program | AGT Ch 5-6 | Kroer |
| 14 | 3 / 9 | Market equilibrium abstraction,  Internet ad auctions | | Kroer |
| 15 | 3 / 11  | A-CEEI: Matching students to courses | [A-CEEI paper](/papers/a-ceei.pdf), [Solving A-CEEI and applying it at Wharton](/papers/course_match.pdf) | Kroer |
| - | 3 / 16 | Spring break |  | | 
| - | 3 / 18 | Spring break |  | | 
| 16 | 3 / 23 | Allocation of food to food banks | Prendergast. The Allocation of Food to Food Banks. Working paper, 2017. [pdf](https://faculty.chicagobooth.edu/canice.prendergast/research/foodwithmodel.pdf)  | Kroer |
| 17 | 3 / 25 | Spectrum auctions | Cramton. Spectrum Auction Design, 2013. [pdf](http://www.cramton.umd.edu/papers2005-2009/cramton-spectrum-auction-design.pdf) Fréchette, Newman, & Leyton-Brown. Solving the Station Repacking Problem. AAAI, 2016. [pdf](http://www.cs.ubc.ca/~kevinlb/pub.php?u=2016-AAAI-SATFC.pdf) | Kroer |
| 18 | 3 / 30 |  | | Kroer |
| 19 | 4 / 1 |  | | Kroer |
| 20 | 4 / 6 |  | | Kroer |
| 21 | 4 / 8 |  | | Kroer |
| 22 | 4 / 13 |  | | Kroer |
| 23 | 4 / 15 |  | | Kroer |
| 24 | 4 / 20 |  | | Kroer |
| 25 | 4 / 22 |  | | Kroer |
| 26 | 4 / 27 |  | | Kroer |
| 27 | 4 / 29 |  | | Kroer |
| 28 | 5 / 4 |  | | Kroer |


### Related Courses

Below is a list of related courses at other schools. 

| Professor | Title | Year | School |
|-----------|-------|------|--------|
| John P. Dickerson | [ Applied Mechanism Design for Social Good ](https://www.cs.umd.edu/class/spring2018/cmsc828m/) | 2018 | UMD |
| Fei Fang | [ Artificial Intelligence Methods for Social Good ](https://feifang.info/artificial-intelligence-methods-for-social-good-spring-2018/) | 2018 | CMU |
| Yiling Chen | [ Topics at the Interface between Computer Science and Economics ](https://canvas.harvard.edu/courses/9622) | 2016 | Harvard |
| Vincent Conitzer | [ Computational Microeconomics: Game Theory, Social Choice, and Mechanism Design ](http://www.cs.duke.edu/courses/spring16/compsci590.4/) | 2016 | Duke |
| Sanmay Das | [ Multi-Agent Systems	 ](http://www.cse.wustl.edu/~sanmay/teaching/cse516-spring16/) | 2016 | Wash U |
| Ariel Procaccia | [ Truth, Justice, and Algorithms ](http://www.cs.cmu.edu/~arielpro/15896s16/index.html) | 2016 | CMU |
| Milind Tambe | [ Security and Game Theory	 ](http://teamcore.usc.edu/Courses/ISE599/) | 2016 | USC |
| Constantinos Daskalakis | [ Games, Decision, and Computation ](https://stellar.mit.edu/S/course/6/sp15/6.891/index.html) | 2015 | MIT |
| Tuomas Sandholm | [ Foundations of Electronic Marketplaces	 ](http://www.cs.cmu.edu/~sandholm/cs15-892F15/cs15-892.htm) | 2015 | CMU |
