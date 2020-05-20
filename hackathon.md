---
layout: page
title: Hackathon
subtitle: Online hackathon - 23-24 July 2020.
---

# Introduction
To allow further investigation of the methods used in the original challenge, the challenge organizers have asked the participants to submit their algorithms / workflows in such a way that they can be repeated for different test and training data sets. The standardized codebase can also serve as an exemplar for future code-sharing initiatives in medical computing. Some challenge participants have already shared their algorithms. We plan to organize a hackathon in July to continue the TADPOLE-SHARE initiative. 

# Objectives
1.	To create a standardized codebase for TADPOLE algorithms
2.	To implement TADPOLE algorithms in the platform
3.	To reproduce TADPOLE results using the TADPOLE-SHARE implementation of algorithms
4.	To validate TADPOLE-SHARE algorithms on an external testing dataset
5.	To write a manuscript on TADPOLE-SHARE and generalizability of algorithms to external testing dataset

# Status per objective (March 2020)
1.	We created a standardized codebase for TADPOLE algorithms. Information can be found here: https://tadpole-share.github.io/
2.	We implemented 3 algorithms. For BenchmarkLastVisit, very simple algorithm that I did not write myself, this took me 3 hours. Most work is restructuring into preprocess, train and predict functions. We still need to implement other algorithms.
3.	Not done for the 3 algorithms yet. Currently predictions are done on a subset of D1D2 data. We need to create a processing function for loading training and testing data in the challenge format and evaluate results. 
4.	We will use data from the Parelsnoer Neurodegenerative Diseases study for this. Data from 8 centers in the Netherlands, N=556. All data has been collected, but should be put into correct format before we can start analysis. 

# Why a hackathon?
TADPOLE-SHARE has only implemented 3 algorithms so far. Main reason for this low number is that code was generally written with the aim of challenge participation (with a deadline) and not to be good quality, readable and reusable code. The major effort of TADPOLE-SHARE therefore turned out to be the cleaning and restructuring of the algorithms. We tried to get this work done by research software engineers, but this did not work out. For this work, given the status of most code, knowledge on the algorithm is needed and therefore this can only be done by the original authors. 
This is the main reason we are taking the initiative of this hackathon. We would like to give motivated TADPOLE participants the opportunity to travel to the Netherlands (for the hackathon and AAIC). We would like participants to prepare their code for TADPOLE-SHARE, work together to implement the code into the codebase and evaluate them, and finally become co-author on a publication. 

# Team 
* Esther Bron, Erasmus MC (PI)
* Lotte Mulder, Erasmus MC
* Vikram Venkatraghavan, Erasmus MC
* Razvan Marinescu, MIT
* Neil Oxtoby, UCL
* Maarten van Meersbergen, eScience Center
* Carlos Martinez Ortiz, eScience Center

# Hackathon plan
Role of hackathon participants
* Before the hackathon, we would like you to be prepared: 1) Take a look at the example algorithms of TADPOLE-SHARE and try to run them, 2) Make sure you understand your algorithm and that all steps are fully automatic, 3) Rewrite you algorithm into a preprocess, train and prediction function.
* During the hackathon, you will add the algorithm to the TADPOLE-SHARE code base and evaluate it on TADPOLE data to test if results are reproduced. We will also presentations by all participants and a social program. The external dataset that will be used in the manuscript will be available. If time allows, testing on this set can start. 
* After the hackathon, TADPOLE-SHARE organizers will evaluate all algorithms on the external dataset and prepare a manuscript on which you will be co-author. 

# Preliminary agenda (open for suggestions!):
*	Tuesday 23 July
 * Short pitches by participants on their methods
 * Presentation on TADPOLE-SHARE and Parelsnoer dataset (Esther)
 *	Hands-on session: adding algorithms to the TADPOLE-SHARE code base
*	Friday 24 July
 *	Hands-on session: evaluation of reproducing TADPOLE results (optional: Parelsnoer dataset)
 *	Brainstorm on manuscript (Other interesting datasets?)
We will make a detailed programme, taking account of timezones of participanting teams.
 
# Longitudinal / cross-sectional methods (D2/D3 datasets)
Both longitudinal (D2) and cross-sectional (D3) methods can be implemented in the TADPOLE-SHARE framework and both contributions qualify for co-authorship on the TADPOLE-SHARE manuscript. For reproducing the TADPOLE results (Objective 3), all implemented methods, both cross-sectional and longitudinal, will be used. For external validation (objective 4), only cross-sectional methods will be used. 

# Algorithms in Matlab or R
TADPOLE-SHARE is python based. For R and Matlab algorithms the preparations steps are identical to those for the python algorithms: rewrite into preprocess, train and predict functions. However, they can only be incorporated in the code base if they can be called from python function. 

# Analysis and manuscript
The manuscript will consist of the following elements:
* Presentation of the TADPOLE-SHARE framework
* Reevaluation of the TADPOLE paper results using the TADPOLE-SHARE implementation.
* Evaluation of the trained TADPOLE-SHARE algorithms on Parelsnoer data. 

# Timeline
23-24 July 2020: 	TADPOLE-SHARE Hackathon, online
1-3 September 2020: 	CompAge, Paris. Hand-on session

# Questions
Esther Bron - e.bron@erasmusmc.nl