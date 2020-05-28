---
layout: page
title: Hackathon
subtitle: Online hackathon - 23-24 July 2020.
---

## Welcome to the TADPOLE-SHARE Hackathon! 

To allow further investigation of the algorithms of the TADPOLE challenge, we initiated a standardized codebase for TADPOLE algorithms: TADPOLE-SHARE. We are collecting TADPOLE algorithms in such a way that they can be applied to different test and training data sets. The standardized codebase can also serve as an exemplar for future code-sharing initiatives in medical computing. Currently, three algorithms are implemented in this codebase. The aim of the TADPOLE-SHARE is to extend this collection and to validate the implemented algorithms on an external dataset. 

The main reason for organizing this hackathon is that in-depth knowledge of the algorithm is essential for implementation of the algorithms in the codebase and therefore this can only be done by the original authors. We would like participants to prepare their code for TADPOLE-SHARE, work together to implement the code into the codebase and evaluate them, and finally become co-author on a publication.

## Objectives
1. To reproduce TADPOLE results using the TADPOLE-SHARE implementation of algorithms (*to be finished during hackathon*).
2. To validate TADPOLE-SHARE algorithms on an external testing dataset (i.e. Parelsnoer Neurodegenerative Diseases study, N=556) (*to be started during hackathon*).
3. To write a manuscript (*after the hackathon*) containing:
- Presentation of the TADPOLE-SHARE framework.
- Reevaluation of the TADPOLE paper results using the TADPOLE-SHARE implementation.
- Evaluation of the trained TADPOLE-SHARE algorithms on external data.

## Program

|  | *Thursday July 23* |
| ------------ | ------------- |
| 09.00-14.00 CEST: | *Hands-on time*\*<br>Short update meetings will be planned with all European and Asian teams separately. |
| 14.00-15.30 CEST: | *Hackathon Official Opening*<br>1. Introduction by TADPOLE-SHARE organizers (~15 mins)<br>2. Pitch by each participating team (~10 mins each)<br> - Introduce yourself, including some fun pictures of team members.<br> - Brief explanation of your algorithm.<br> - What are your goals and expectations for this hackathon. |
| 15.30-17.00 CEST: | *Hands-on time*\*<br>Short update meetings will be planned with all North-/Latin-American teams. |

<br style="line-height:0px;" /> 

|  | *Friday July 24* |
| ------------ | ------------- |
| 09.00-14.00 CEST: | *Hands-on time*\*<br>Short update meetings will be planned with all European and Asian teams separately. |
| 14.00-15.30 CEST: | *Hackathon Official Closing*<br>1. Short progress update by each participating team.<br>2. Brainstorm on TADPOLE-SHARE analysis and manuscript. <br> - After the hackathon, we will evaluate the algorithms on the external dataset.<br> - We will prepare a manuscript on which you will be co-author.<br> - Ideas are very much appreciated.<br> |
| 15.30-17.00 CEST: | *Hands-on time*\*<br>Short update meetings will be planned with all North-/Latin-American teams. |

\* *Hands-on time and the rest of the days are meant for teams to work on implementation of algorithms in the TADPOLE-SHARE framework. The goal is to add the algorithms to the TADPOLE-SHARE code base and evaluate them on TADPOLE data to validate if challenge results are reproduced. The external dataset that will be used in the manuscript will be available to start the evaluation. During the hands-on time (9-14h CEST; 15.30-17h CEST):*
- *Organisers are available for questions on framework and evaluation strategy.*
- *Research software engineers are available for questions on implementation and Python.*
- *Teams can collaborate using Slack, Zoom and Visual Studio Code.*

## Teams
Seven teams have signed up to participate in the challenge. We are planning a meeting with each team in the first week of July. In those meetings, we would like to discuss any questions the teams have as well as the expectations of the hackathon, the current status of their algorithms and the expertise or help they expect to need.

## Platforms
The hackathon will take place online, using the following platforms:
- *Website:* [Central place](https://tadpole-share.github.io/hackathon/) for information and announcements.
- *Slack:* Main communication channel before and during the hackathon. Please, join our [Slack channel](
https://join.slack.com/t/tadpole-hq/shared_invite/zt-9mhtywyc-S37gj3PFZ2bWDZc2t6u7xw).
- *Zoom:* All presentations and collaboration sessions will be held on Zoom. Zoom links will be shared in Slack.
- *Visual Studio Code:* Collaboration sessions will use Visual Studio Code for working on the same code live. Download [Visual Studio Code](https://code.visualstudio.com/) and the [Live Share Extension](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare).

## Preparation
1. Get familiar with the TADPOLE-SHARE framework by running existing algorithms: [Tutorial](https://docs.google.com/document/d/19cj8_GPxugFJyTh88i_jrskyMh68QsrIqrqKiT7Dn0U/edit).
2. Prepare your algorithm: 
- Make sure you understand your algorithm and that all steps are fully automatic.
- The TADPOLE-SHARE framework is written in Python 3. Therefore, only algorithms that can be run from Python 3 can be implemented. So, if your algorithm is not in Python this means that you may have to do some extra work. The preferred option is to rewrite the code in python. Alternatively, you can explore options to call the R or Matlab code from Python. If none of the previous options are possible, we recommend to still adapt the structure of the algorithm to the TADPOLE-SHARE structure with separate train and predict functions. If time allows, we could explore dockerizing the algorithms during the hackathon. Please inform us what option you choose. 
- Both longitudinal (D2) and cross-sectional (D3) methods can be implemented in the TADPOLE-SHARE framework. For reproducing the TADPOLE result, all implemented methods -both cross-sectional and longitudinal- will be used. For external validation, only cross-sectional methods will be used.
3. Implement your algorithm into the TADPOLE-SHARE framework: [Tutorial](https://docs.google.com/document/d/18rUQRi0rIelpNtDNJqYhPYbNhD20-zszSwKuHNUtPuk/edit).
4. Prepare a short pitch for the Opening Session.

## Organizers
- Esther Bron, Erasmus MC (PI)
- Lotte Mulder, Erasmus MC
- Vikram Venkatraghavan, Erasmus MC
- Neil Oxtoby, UCL
- Razvan Marinescu, MIT
- Maarten van Meersbergen, eScience Center
- Carlos Martinez Ortiz, eScience Center

## Questions?
Contact the organizers via Slack or e.bron@erasmusmc.nl
