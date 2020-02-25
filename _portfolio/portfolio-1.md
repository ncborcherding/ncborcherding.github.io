---
title: "TRGAted"
excerpt: "Prognostic calculator using protein-level TCGA data across 31 cancer types."
collection: portfolio
---

![]("https://github.com/ncborcherding/ncborcherding.github.io/blob/master/images/TRGAted.png", align="center")

Reverse-phase protein arrays (RPPAs) are a highthroughput approach to protein quantification utilizing antibody-based micro-to-nano scale dot blot. Within the Cancer Genome Atlas (TCGA), RPPAs were used to quantify over 200 proteins in 8,167 tumor and metastatic samples. Protein-level data has particular advantages in assessing putative prognostic or therapeutic targets in tumors. However, many of the available pipelines do not allow for the partitioning of clinical and RPPA information to make meaningful conclusions. We developed a cloud-based application, [TRGAted](https://nborcherding.shinyapps.io/TRGAted/) to enable researchers to better examine patient survival based on single or multiple proteins across 31 cancer types in the TCGA. TRGAted contains up-to-date overall survival, disease-specific survival, disease-free interval and progression-free interval information. Furthermore, survival information for primary tumor samples can be stratified based on gender, age, tumor stage, histological type, and subtype, allowing for highly adaptive and intuitive user experience. The code and processed data are open sourced and available on [github](https://github.com/ncborcherding/TRGAted) and contains a tutorial built into the application for assisting users. Full details on the development and implementation is available at [F1000Research](https://f1000research.com/articles/7-1235/v2).

