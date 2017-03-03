---
date: 2017-02-22T17:00:00+01:00
title: The LABSIM Simulation Software Ecosystem
weight: 20
---

## Scientific fields 

<br>

The LABSIM simulatiom software ecosystem mainly cover 2 Applied Computer Science sub-fields :
 
* Distributed Systems.

* Software Engineering.

And a much more transverse one :

* **VR** (**V**irtual-**R**eality) and it's extension **AR** (**A**ugmented-**R**eality) & **MR** (**M**ixed-**R**eality).

<br>

---

## Problematic 

<br>

Every answer is the consequence of a questionning, even the most trivial one. That said, for our case, the LABSIM was created to anwser the following problematic :

> **How to allow fast & early conception/evaluation cycle of innovative concept** ***in situ*** **?**

Given these initials conditions :

* Human-system interactions & human factors sub-team

* Rotorcraft system sub-team

<br>

*Hum ?...* Let's decompose & analyse each significant term of our problematic :

* [...] **fast & early conception** [...] :

  * obviously, this lead us to rapid system prototyping.

  * by the way, time is money, so if you want something to be setup quickly it has to be a cheap or relatively afordable solution => simulation.

* [...] **fast & early evaluation** [...] :

  * to evaluate something, we need to be representative/immersive enough.

  * it also mean that we will probably have to handle wide range of heterogenous data acquisition sensor.

  * and because we are scientist, we will have to provide a data warrantly => consistency.

* [...] **cycle** [...] :

  * reliability & repeatability.

* [...] **innovative concept** [...] :

  * innovative concept lead to domain specific expert.

  * we do computer sciences so we should leaverage this aspect from them => focus on key competencies *(reminder: initials conditions)*

  * innovation is a blend, a fusion of various scientific domain.

* [...] ***in situ*** [...] :

  * human **is in the loop** => human centered design.

  * human don't lag so we should focus on performance with near real-time recquirements => soft real-time ~100Hz

  * human centered + computer science => Virtual Reality principles !

  * lastly, because we are an in-house lab from the [**ONERA**](http://www.onera.fr/), by *human* we mean *pilot, UAV/ATC operator, ...*   

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

Why performance matters ? Because.

* When studying the effect of various latency on the human sense of control over an automated system (agency), *performance is critical.*

* When prototyping a representative fight dynamic mode requiring regular continuous time clock and tight time resolution, *performance is critical.*

* When exploring the optimality of a movement produced by the human motricity system during a specific piloting task, *performance is critical.*

* When dealing with human in a simulated virtual environment, *performance is critical*.

* And more [..]

For us, perfomance is not just a fancy word. It's our credibility.

<br> 

### 3. Code-less

Leave the computer sciences complexity to us and provide you :

* **SAAS** (**S**imulation **A**s **A** **S**ervice), abstracting the hardware integration development problematics.

| |
| :---: |
| ![sketch_HW](/img/sketch/hw_sim_whitebox.png) |

* generic model **API** (**A**plication **P**rogramming **I**nterface), abstracting the software development problematics.

| |
| :---: |
| ![sketch_API](/img/sketch/sw_simple_api.png) |
| *Yep, i know. pretty simple. that's the point :)* |


* performant **WYSIWYG** (**W**hat **Y**ou **S**ee **I**s **W**hat **Y**ou **G**et) tools to setup a simulation.

* for the guru, a **DIY** (**D**o **I**t **Y**ourself) pipeline shorcut through a fully **XML** (e**X**tended **M**arkup **L**angage) based environment.

<br>

### 4. Multi-disciplinar

Innovate, mix, blend...

| |
| :---: |
| ![sketch_multidisciplinar](/img/sketch/multidisciplinar_sim_composition_5.png) |

### 5. Modular

Simulation-to-simulaton modularity, fastening iteration.

| |
| :---: |
| ![sketch_sim_to_sim](/img/sketch/sim_to_sim_arch_composition_4.png) |

---

## Software Architecture

| |
| :---: |
| ![sketch_soft_arch_0](/img/sketch/data_centric_arch_0.png) |

| |
| :---: |
| ![sketch_soft_arch_1](/img/sketch/data_centric_arch_1.png) |

| |
| :---: |
| ![sketch_soft_arch_6](/img/sketch/data_centric_arch_6.png) |

| |
| :---: |
| ![sketch_soft_arch_7](/img/sketch/data_centric_arch_7.png) |

| |
| :---: |
| ![sketch_soft_arch_8](/img/sketch/data_centric_arch_8.png) |

| |
| :---: |
| ![sketch_soft_arch_9](/img/sketch/data_centric_arch_9.png) |

| |
| :---: |
| ![sketch_soft_arch_10](/img/sketch/data_centric_arch_10.png) |

| |
| :---: |
| ![sketch_kronos_rhea_arch](/img/sketch/kronos_rhea_sw_arch_7.png) |

| |
| :---: |
| ![sketch_thetys_ocean_arch_18](/img/sketch/thetys_ocean_sw_arch_18.png) |

| |
| :---: |
| ![sketch_thetys_ocean_arch_25](/img/sketch/thetys_ocean_sw_arch_25.png) |

| |
| :---: |
| ![sketch_titans_arch_3](/img/sketch/titans_global_sw_arch_3.png) |

| |
| :---: |
| ![sketch_titans_arch_4](/img/sketch/titans_global_sw_arch_4.png) |

| |
| :---: |
| ![sketch_titans_arch_5](/img/sketch/titans_global_sw_arch_5.png) |

| |
| :---: |
| ![sketch_titans_arch_6](/img/sketch/titans_global_sw_arch_6.png) |

---

## Software Topology

| |
| :---: |
| ![sketch_soft_topo](/img/sketch/sw_medium_topographie_4.png) |

| |
| :---: |
| ![sketch_hw_topo](/img/sketch/hw_medium_topographie_9.png) |

---

## Model Integration Pipeline

| |
| :---: |
| ![sketch_pipeline](/img/sketch/LABSIM_pipeline_simplified_10.png) |

---

## Simulation Composition Pipeline

*You can always get back or discover our landing site* ***[here](https://labsim.github.io)*** :)
