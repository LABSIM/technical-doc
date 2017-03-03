---
date: 2017-02-22T17:00:00+01:00
title: The LABSIM Simulation Software Ecosystem
weight: 10
---

## Scientific fields 

<br>

The LABSIM simulatiom software ecosystem mainly cover 2 Applied Computer Science sub-fields :
 
* Distributed Systems.

* Software Engineering.

And a much more transverse one :

* **VR** (Virtual-Reality) and it's extension **AR** (Augmented-Reality) & **MR** (Mixed-Reality).

<br>

---

## Problematic 

<br>

Every answer is the consequence of a questionning, even the most trivial one. There is no *divine* answer because we do science ! That said, in our case, the LABSIM was created to anwser the following problematic :

> **How to allow fast & early conception/evaluation cycle of innovative concept** ***in situ*** **?**

Given these initials conditions :

* Human-system interactions & human factors sub-team

* Rotorcraft system sub-team

<br>

*Hum ?...* Let's decompose & analyse each significant term of our problematic :

* [...] **fast & early conception** [...] :

  1. obviously, this lead us to system prototyping.

  2. by the way, time is money, so if you want something fast it has to be cheap => simulation.

* [...] **fast & early evaluation** [...] :

  1. to evaluate something, we need to be representative/immersive enough.

  2. it also mean that we will probably have to handle wide range of heterogenous data acquisition sensor.

  3. and because we are scientist, we will have to provide a data warrantly => consistency.

* [...] **cycle** [...] :

 1. reliability & repeatability.

* [...] **innovative concept** [...] :

  1. innovative concept lead to domain specific expert.

  2. we do computer sciences so we should leaverage this aspect from them => focus on key competencies *(reminder: initials conditions)*

  3. innovation is a blend, a fusion of various scientific domain.

* [...] ***in situ*** [...] :

  1. human **is in the loop** => human centered design.

  2. human don't lag so we should focus on performance with near real-time recquirements => soft real-time ~100Hz

  3. human centered + computer science => Virtual Reality principles !

  4. lastly, because we are an in-house lab from the [**ONERA**](http://www.onera.fr/), by *human* we mean *pilot, UAV/ATC operator, ...*   

<br>

---

## Guidelines 

<br>

So, until now, as a result of our previous resonning and as a rule of thumb, we stated 5 guidelines since early conception stage of the LABSIM simulation software ecosystem. And these rules are not something we get out of nowhere, they are not the result of a hype brainstorming that we could have held once in a really secret HQ with superstar dev & amazing buisnessman. 

Well... ***Nope***. 

They are what researcher *care about* when they have deal with *real-time piloted simulation studies*. They simply are the "polished" needs of our rearcher. *Our answer*. As simple as it sounds. At least, we *hope* it is :)

<br>

### 1. Human-centered

Once again, *soft real-time piloted simulation*. 

And by piloted, we mean that our subject of interest is mainly a human beeing operator and our evaluation criteria could be : simulation fidelity, acceptability, ergomomy, piloting performance, neuroergonomy, agency, sense of control, multi-agent collaboration... So, we naturally design our ecosystem to match some human-oriented design theory for real-time simulation, as said, the **VR**.

Our main source of inspiration came from these two sketches.

| |
| :---: |
| ![sketch_loop_VR](/img/sketch/perception-cognition-action-loop.png) |
| *Perception, cognition, action loop* |

| |
| :---: |
| ![sketch_tech_VR](/img/sketch/techno-centric-approch-VR.png) |
| *Technocentric reference scheme in VR* |

### 2. Performance focused 

### 3. Modular

### 4. Multi-disciplinar

### 5. Code-less

## Software Topology

## Software Architecture

## Model Integration Pipeline

## Simulation Composition Pipeline

*You can always get back or discover our landing site* ***[here](https://labsim.github.io)*** :)
