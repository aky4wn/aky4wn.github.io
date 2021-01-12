---
layout: page
title: Research
permalink: /research/
---

My current research projects focus on probabilistic modeling for structured time series, with applications for audio data and retail demand forecasting.  I am particularly interested in developing time series models that accurately represent uncertainty, while achieving high forecast accuracy.


## Hierarchical Multidimensional Scaling


![](X-tsne-tempo2.png){:style="float: right; height="50%" width="50%"}
We develop a hierarchical multidimensional scaling (HMDS) method to quantify systematic differences across heterogeneous, replicate distance matrices, where each replication has its own potential for variation.  HMDS allows for the systematic component of each replicate distance matrix to be non-Euclidean and can separate variation due to a non-Euclidean mean distance from measurement error. We develop an audio pre-processing methodology and apply the proposed HMDS model to quantify the differences between 10 different orchestras across the 9 Beethoven symphonies.
 

- A.K. Yanchenko and P.D. Hoff. **Hierarchical Multidimensional Scaling for the Comparison of Musical Performance Styles.** *Annals of Applied Statistics*, 14(4):1581-1603, 2020. [[DOI](https://projecteuclid.org/euclid.aoas/1608346888) \| [arXiv](https://arxiv.org/abs/2004.13870) \| [code](https://github.com/aky4wn/HMDS)]


## Personalized Forecasting

This project focuses on personalized forecasting of many time series in a retail setting.  We require models that are probabilistic, hierarchical and interpretable to improve forecasting of heterogeneous individual-level purchasing trends.  Probabilistic inference and forecasting allows for downstream decisions and interventions in the model.


- A.K. Yanchenko, D. Deng, J. Li, A.J. Cron and M. West. **Hierarchical Dynamic Modeling for Bayesian Individualized Forecasting.** 2021 (submitted). [[arXiv](https://arxiv.org/abs/2101.03408)]

## Stanza

![](Lorenz-r=5.png){:style="float: right; height="40%" width="40%"}
Stanza is a nonlinear, non-stationary state space model designed to balance competitive forecasting accuracy and probabilistic, interpretable inference for structured time series. Stanza is intended as an intermediate approach between traditional state space models and full attention-based deep learning approaches.   



- A.K. Yanchenko and S. Mukherjee. **Stanza: A Nonlinear State Space Model for Probabilistic Inference in Non-Stationary Time Series.** 2020. [[arXiv](https://arxiv.org/abs/2006.06553)]


<!---
## Audio Representation Learning

Representation learning for audio signals is a challenging task, especially for complex signals arising from orchestral classical music.  This ongoing project looks to extend preliminary findings in the [Symphony2Vec](https://aky4wn.github.io/code/) project to learn a meaningful, disentangled latent representation for complex audio with known long term structure.

-->

