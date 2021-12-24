---
layout: page
title: Probabilistic Manipulation with LTLf
permalink: /probabilstic-manipulation/
---

# Probabilistic Manipulation with LTLf

![Probabilistic Manipulation](/assets/probabilistic_manipulation.png)

We use Linear Temporal Logic over finite traces (LTLf) to specify a goal. Then we synthesize an optimal policy using the PRISM model checker. While reactive synthesis deals with the worst case (and can thus provide stronger guarantees), probabilistic synthesis deals with the best case (and can thus be more efficient).

Consider a robot that wants to build an arch with a human present. The robot knows the human is more likely to intervene when the arch is nearby. Depending on the model of the human, the robot may choose to minimize human interventions (a) by building the arch further away or to encourage interventions (b) by building the arch near the human.

[Paper](http://kavrakilab.org/publications/wells2021-finite-horizon-synthesis.pdf)

[Code on Github](https://github.com/KavrakiLab/probabilistic_manipulation)

[Video on Google Drive](https://drive.google.com/file/d/1OSoq-ef7TpEi7D4AnKVxrXObt6cJApV_/view?usp=sharing)