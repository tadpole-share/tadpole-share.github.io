---
layout: page
title: TADPOLE-SHARE
subtitle: SHaring TADPOLE’s Algorithms for Reuse and Evaluation
bigimg: /img/Tadpole_groot.jpg
---

This website is part of the [TADPOLE-SHARE project](https://www.esciencecenter.nl/project/tadpole-share) awarded to [Esther Bron](https://www.esciencecenter.nl/news/the-winner-of-the-young-escientist-award-2018-is) (Erasmus MC) by the [Netherlands eScience Center](https://www.esciencecenter.nl/). This project builds upon the [TADPOLE challenge](https://tadpole.grand-challenge.org/) and provides an example of how algorithms for predicting Alzheimer’s disease can be made available for further development and re-use. We provide tutorials and example code for the EMC-EB algorithm that participated in the TADPOLE challenge.

### The TADPOLE challenge

The [challenge](https://tadpole.grand-challenge.org/) on which this project was based was concluded on the 16th of November 2017, with a [paper](https://arxiv.org/abs/1805.03909) submitted on the 11th of May 2018. The goal of this challenge was twofold:
- Identify individuals that are likely to need and respond to treatment. AD treatments are most likely to be effective at early disease stages, even before any outward signs of dementia.
- Accurately predict the change in disease indicators so that we can assess the effect of the treatment.

During the course of this challenge several machine learning algorithms were created to tackle these research questions. 

### The Shared TADPOLE Algorithms

Several algorithms were shared following a call by the challenge organizers, to be used as the codebase for TADPOLE-SHARE. 

- [EMC1](https://github.com/tadpole-share/TADPOLE_submission_with_debm)
- [Borre](https://github.com/tadpole-share/borre)

### Try it yourself!

The conda environment created by the Netherlands eScience Center will allow users to quickly deploy a Jupyter Notebook to try (and tweak) the algorithms, which saves a copious amount of hassle for beginners. This will hopefully inspire newcomers to the field of alzheimer prediction to try their own variations, and to see if they can improve upon the accuracy or speed of the predictions.

[TRY IT OUT!](https://github.com/tadpole-share/jupyter)

### Make your own algorithm compatible

In the [ECM-EB](https://github.com/tadpole-share/EMC-EB) repository, the Netherlands eScience Center has made an effort to generalize one of the algoritms for further use. This repository will now function as a template for other algorithms which want to benefit from this approach as well. In this repository, we have made sure that the code conforms to the FAIR standards for open and reproduceable science.
