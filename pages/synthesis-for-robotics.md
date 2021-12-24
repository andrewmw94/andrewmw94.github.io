---
layout: page
title: Synthesis for Robotics
permalink: /synthesis-for-robotics/
exclude: true
---

# Synthesis for Robotics

![Synthesis for Robotics](/assets/synthesis_for_robotics.png)

We consider two types of synthesis. The first is reactive synthesis, where the system (robot) and environment (human) choose their actions. We formulate this as a game where the robot and human play against each other. This provides strong guarantees, as the robot must deal with worst-case human behaviors. On the other hand, the worst-case is frequently too pessimistic. [Efficient Symbolic Reactive Synthesis for Finite-Horizon Tasks](http://dx.doi.org/10.1109/ICRA.2019.8794170)

In the second type, we consider probabilistic synthesis. Here the system (robot) makes choices while the environment (human) is stochastic. This allows us to deal with expected-case behaviors, but leads to challenges modeling the human. [LTLf Synthesis on Probabilistic Systems](http://dx.doi.org/10.4204/eptcs.326.11)

We present probabilistic synthesis for robotic manipulation domains on [Probabilistic Manipulation with LTLf](https://www.andrewmwells.com/probabilistic-manipulation-with-ltlf/) The key improvement compared to reactive synthesis is the ability to deal with the expected case rather than being limited to the worst case. This can enable more efficient human-robot collaboration.