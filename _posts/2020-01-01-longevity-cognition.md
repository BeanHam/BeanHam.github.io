---
layout: post
title: "Exceptional Longevity & Normal Cognition"
author: "Bin Han"
categories: journal
tags: [documentation, sample]
image: longevity-cognition.jpg
---

**Paper Synopsis: [Genetic and non-genetic factors associated with the phenotype of exceptional longevity & normal cognition](https://www.nature.com/articles/s41598-020-75446-2)**

📖📖📖📖📖📖📖📖📖📖 📖📖📖📖📖📖📖📖📖📖📖📖📖📖

Cognitive Impairment (CI) is defned as the loss of ability in cognitive functions, such as remembering, learning, and concentrating, which negatively impacts affected individuals’ daily activities. In the stage of mild cognitive impairment (MCI), affected individuals start to experience memory issues without seriously hindering their abilities to execute daily activities. In the stage of severe cognitive impairment, which is referred as dementia, individuals tend to lose basic functionalities of comprehending, memorizing, or even talking and writing. Many diseases are associated with the development of CI, such as Alzheimer’s Disease (AD), Vascular Dementia, Parkinson’s Disease (PD), Progressive Supranuclear Palsy, and Lewy Body Disease.

There have been previous studies on the pertinent factors associated with cognitive impairment. For example, using discovery and multiple replication cohorts, Davies et al. identifed several significant genetic loci that are associated with CI, such as *rs2075650* and *rs115566* located in *TOMM40* and *rs429358* located in the APOE region. Lv et al. probed the association between the rate of cognitive decline and the mortality rate. They concluded that faster cognitive decline rate is associated with higher mortality rate, specifcally among individuals aged between 65-79 years old and cognitively normal individuals, regardless of their initial cognitive abilities. With respect to the analysis on non-genetic factors, Casanova et al. constructed a random forest model to investigate important predictors for cognitive trajectories, identifying education, age, and gender, as top predictors. Many other studies have also analyzed the genetic and non-genetic contributors to CI in community-based cohorts. Nevertheless, there are few studies that analyze the effects from both genetic and non-genetic factors on CI to our knowledge. Consequently, the primary goal of our research is to investigate which factors, both genetic and non-genetic, are signifcantly associated with cognitive impairment, in contrast to intact cognition in late life. 

In our study, we split 2156 individuals from the Chinese Longitudinal Healthy Longevity Survey (CLHLS) data into two groups, establishing a phenotype of exceptional longevity & normal cognition versus cognitive impairment. We conducted a genome-wide association study (GWAS) to identify signifcant genetic variants and biological pathways that are associated with cognitive impairment and used these results to construct polygenic risk scores. We elucidated the important and robust factors, both genetic and non-genetic, in predicting the phenotype, using several machine learning models.

The GWAS identifed 28 signifcant SNPs at $p<3e10^{-5}$ signifcance level and we pinpointed four genes, *ESR1, PHB, RYR3, GRIK2*, that are associated with the phenotype though immunological systems, brain function, metabolic pathways, infammation and diet in the CLHLS cohort. Using both genetic and non-genetic factors, four machine learning models have close prediction results for the phenotype measured in Area Under the Curve: random forest (0.782), XGBoost (0.781), support vector machine with linear kernel (0.780), and ℓ2 penalized logistic regression (0.780). The top four important and congruent features in predicting the phenotype identifed by these four models are: polygenic risk score, sex, age, and education.

*image source: https://www.medicalnewstoday.com/articles/320204
