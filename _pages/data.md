---
permalink: /data/
title: "Open Data"
---

## RECAP Artificial Data Traces

Throughout the course of the project, RECAP has collected a large amount amount of data.
In an effort to increase transparency and research speed, RECAP has opted to release real and artificial workloads aiding in the research process throughout the field of cloud computing.

Data on:

* Infrastructure and Network Management
* Big Data Analytics
* Edge/Fog Computing for Smart Cities
* Virtual Content Delivery Networks

Was provided by the RECAP partners and extended using algorithms for synthetic workload generation such as:

* Structural Models based Workload Generation
* Regression-Model-based Workload Generation
* GAN-based Workload Generation
* Traffic Propagation based Workload Generation

The work was performed as part of WP5.
The objective of the WP5 – Data Collection, Visualization and Analysis of RECAP is to provide the necessary tools for managing and refining the data needed for the rest of the work packages. This includes the collection as well as the generation of data.
Within this work package, Task 5.3 Artificial Workload Generation is responsible for the generation of a collection of datasets with artificial workloads, that complement the real data traces collected from industrial partners. Moreover, because publicly available workload data is scarce we provide the data as public data sets.
This document released with the data is a companion report to Deliverable D5.3 which is of type “dataset”. The aim of the report is to describe the collection of datasets that constitute D5.3 and the mathematical techniques (structural time series models, generative adversarial networks, and workload based on traffic propagation) by which one can artificially generate and/or augment such datasets.
The datasets described include real data traces collected by industrial partners and artificial data traces generated by the use of statistical models and neural networks. Each published data set can be used by the scientific and industrial community as a starting point for the modelling and experimental validation of distributed edge and cloud applications, facilitating the repeatability of the results.

## Download

The data is hosted on [Zenodo](https://doi.org/10.5281/zenodo.3458559).

## Open Access Guidelines

Zenodo is an OpenAire indexed repository for open access publication of scientific work and data.
It meets EU regulations in terms of data publications, and is hosted by CERN with a program defined for the next 20+ years.

## Citation

Please use the follow BibTeX to cite the data:

```TeX
@dataset{leznik_mark_2019_3458559,
  author       = {Leznik, Mark and
                  Garcia Leiva, Rafael and
                  Le Duc, Thang and
                  Svorobej, Sergej and
                  Närvä, Linus and
                  Noya Mariño, Manuel and
                  Willis, Peter and
                  Giannoutakis, Konstantinos M. and
                  Loomba, Radhika and
                  Humanes, Héctor and
                  López, Miguel Ángel and
                  Östberg, P-O and
                  Casari, Paolo and
                  Domaschka, Jörg},
  title        = {RECAP Artificial Data Traces},
  month        = oct,
  year         = 2019,
  note         = {{For details on the data itself, see RECAP- 
                   Artificial Workload Generation.pdf}},
  publisher    = {Zenodo},
  version      = {1.0},
  doi          = {10.5281/zenodo.3458559},
  url          = {https://doi.org/10.5281/zenodo.3458559}
}
```