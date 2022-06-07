---
date: "2022-05-21"
draft: false

research_tags:
- MLOPs
- AI/ML
status: Publication
summary: Instrumenting Machine Learning Operations for Clinical Research
title: MLOps for life sciences
weight: 1
---

Healthcare research and industry have been increasingly progressive in the translation and implementation of Machine Learning (ML) to improve outcomes and lower costs. For a typical healthcare researcher, however, the process of designing and deploying complex ML models on clinical data is not as buttoned-down as running a typical enterprise IT application, such as EHR cohort query tools. On the algorithms, technical advances are made on a regular basis by the broader ML community, mostly in computer vision and language models. However, `Machine Learning Operations (MLOps)` in the context of healthcare data in general, and specifically structured clinical data stored in electronic health records (EHRs), requires `data-centric` approaches to respect the data governance and meet usability and `interpretability` considerations in healthcare. Further, EHR data are known to embody noise, which may be introduced through the recording processes and/or various mechanisms such as observational error, misapplication, and healthcare access inequalities. 

<img src="images/MLOps_healthcare_1.png" alt="MLOps for healthcare" width="600" lign = "center" />
<figcaption align = "center"><b> MLOps for life sciences </b></figcaption>

MLHO’s architecture  enables the operationalization of Machine Learning for clinical research. We discuss that, unlike the mainstream ML solutions that are algorithm-centric, MLHO’s approach is data-centric, recognizing the governance and quality considerations of clinical data.  In other words, MLHO lets us hold the code (ML algorithm) constant, and work on the data. MLHO also incorporates time into the learning process, by allowing for iterative feature and model selection in the modeling lifecycles. As we have experienced in our current and prior research, this feature is specifically suitable for modeling complex phenotypes that may be difficult to define, limited to a distinct temporal period, and evolve over time, such as the Post-Acute Sequelae of SARS-CoV-2 infection (PASC). In addition to our team’s work, so far, multiple researchers across different organizations (and around the world) have begun applying MLHO to different problems, such as defining PASC phenotypes and predicting immunotherapy outcomes. While MLHO’s use cases have been based on research, it can be utilized for the deployment of ML-based applications, in full scale Machine Learning Operations (MLOps) by the addition of a deployment module, in which further unit testing and interface design considerations are added to the evaluation criteria. 
