---
layout: page
title: Projects and Code
permalink: /code/
---
## Algorithmic Composition
<!---
Several ongoing projects focus on generative modeling of classical, orchestral music. The successful modeling of orchestral classical music is an important challenge with applications to many disciplines.  Orchestral classical music is a complex, multivariate time series that is highly structured, both temporally (in terms of melody) and vertically (in terms of harmony).  There are complex dependencies between different instruments, and thus there is a high level of structure both within the part of a single instrument and between instruments.  Music is a long-memory process, with long-term structure over multiple minutes in full orchestral works.  Additionally, the modeling of music is challenging from a data perspective, as there is very little labeled data and it is expensive to obtain, necessitating unsupervised approaches.  Audio data, in particular, while of high interest, is challenging to annotate and label in its raw form. However, music theory provides a source of *ground truth* to assess and validate results.
-->

Several recent projects focus on generative modeling of classical, orchestral music, using state space models, factorial Hidden Markov Models ([Code](https://github.com/aky4wn/Sta863_FHMM)) and dynamic dependency networks  ([Generated Sample]({{ site.url }}/DDNM.mp3)).  Music is interesting from a modeling perspective as music is a long-memory process, with long-term structure over multiple minutes in full orchestral works and is additionally challenging from a data perspective, as there is very little labeled data, necessitating unsupervised approaches.

- A.K. Yanchenko and S. Mukherjee. **Classical Music Composition Using State Space Models.** 2018.  [[arXiv](https://arxiv.org/abs/1708.03822) \| [website](https://aky4wn.github.io/Classical-Music-Composition-Using-State-Space-Models/) \| [code](https://github.com/aky4wn/Classical-Music-Composition-Using-State-Space-Models)]


## Network Analysis of Concert Programming
Additive and Multiplicative Effects network models are applied to the Boston Symphony Orchestra's concert programming. Composer level effects are explored to determine which traits make two composers more likely to be programmed in the same concert together. [arXiv](https://arxiv.org/abs/2009.07887) and [Code](https://github.com/aky4wn/Network-Programming).  This work was also presented as a poster at the Women in Machine Learning Workshop co-located at NeurIPS 2019 in Vancouver  ([Poster]({{ site.url }}/poster.pdf)). Code written in ``R``.


## Symphony2vec: Learning Musically Meaningful Embeddings for Orchestral Audio Data
This project explores the use of Adversarially Learned Inference (ALI) to learn musically meaningful embeddings of orchestral audio data. The goal of this project is to develop a musically meaningful latent representation of orchestral audio recordings that could be used in later generative modeling tasks. The learned embeddings are evaluated on a downstream task of
composer classification. Overall, the adversarially learned inference models explored do not outperform baseline approaches on this classification task, but are able to recover some high-level musically meaningful features in the latent space. Learning a meaningful embedding for audio data remains an open problem and a challenging task. [Report]({{ site.url }}/report.pdf), [Presentation]({{ site.url }}/presentation.pdf) and [Code](https://github.com/aky4wn/Symphony2vec). Code written in ``PyTorch`` and ``Python``.

## Code and Programming Languages
Accompanying code can be found on [GitHub](https://github.com/aky4wn/).
- ``Python``
- ``R``
- ``PyTorch``
- ``Matlab``


<!---
## Music Composition - Independent Study
This project extends some of the previous HMM work for music composition as an independent study by Yuheng (Karl) Ma, as a visiting student at Duke.  I helped mentor this independent study and Karl's code and final report can be found on [GitHub](https://github.com/aky4wn/Music_Composition-Independent_Study). Code written in ``Python``.


## Music Generation with Factorial Hidden Markov Models
This project explores the use of Factorial Hidden Markov Models (FHMMs) to compose classical piano music.  Three different inference algorithms are implemented and compared. The generated pieces tend to be more "original" than pieces generated with basic hidden Markov models, however, the generated pieces still lack  long-term structure.  [Code](https://github.com/aky4wn/Sta863_FHMM), [Report]({{ site.url }}/Yanchenko_FHMM_Report.pdf), [Generated Sample 1]({{ site.url }}/pachelbel_FHMM-GAM.mp3) and [Generated Sample 2]({{ site.url }}/pachelbel_FHMM-SVI.mp3). Code written in ``Python``.

## Variational Inference Tutorial
This tutorial provides an introduction to some important topics in variational inference.  Variational inference is a way to perform posterior inference via optimization, rather than sampling.  The Expectation-Maximization (EM) algorithm is also covered in this tutorial.  The main working example for this tutorial is the Gaussian Mixture Model.  The EM algorithm, variational inference and Markov Chain Monte Carlo methods are all applied to learn the parameters in the Gaussian mixture model.  Inference procedures for each method are derived and discussed. Finally, Latent Dirichlet Allocation is presented as a slightly more advanced example of variational inference.  This tutorial can be found on [GitHub](https://github.com/aky4wn/Tutorials/tree/master/Variational_Inference). Code written in ``Python``.

## NCAA Basketball Tournament Prediction
Various machine learning models are used to try to predict the outcome of the NCAA Men's basketball tournament.  Five different models are implemented and compared, using previous tournament results and current season statistics on each team. In 2019, the majority vote of the ensemble of models implemented correctly predicted 80% of the tournament games.  Code written in ``Python``.

## Polyphonic Music Generation with Dynamic Dependency Network Models 
Dynamic Dependency Network Models (DDNMs) are used to model a four part piano piece, which each voice modeled distinctly.  The DDNM models are succesful at capturing some of the harmony and dependencies between the voices. [Report]({{ site.url }}/Yanchenko_aky5_Sta642_Report.pdf) and [Generated Sample]({{ site.url }}/DDNM.mp3). Code written in ``Python``.

## Latent Dirichlet Allocation
Latent Dirichlet Allocation is implemented from scratch in Python. The implementation is analyzed and applied to movie review data as an example ([Code](https://github.com/aky4wn/663FinalProject)). Code written in ``Python``.

## R Coding Projects
Various R programming projects, including predicting US airline delays ([Code](https://github.com/aky4wn/Predictive-Modeling---Airline-Delays)), comparing NYC boroughs ([Code](https://github.com/aky4wn/NYC-Boroughs-Modeling)), building a simple Shiny application ([Code](https://github.com/aky4wn/Shiny-Bayesian-Analysis)), exploring grpahs in R ([Code](https://github.com/aky4wn/Graphs-in-R)) and using web scraping methods to analyze the locations of restaurants and hotels ([Code](https://github.com/aky4wn/Web-Scraping)). Code written in ``R``.
-->


