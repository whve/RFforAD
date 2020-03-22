---
description: >-
  Database Construction and Genetic Analysis of Environmental Risk Factors for
  Alzheimer's Disease
---

# Background

Despite tremendous advances in understanding the genetic architecture underlying Alzheimer's disease \(AD\), there remains an as yet under-investigated component of risk, namely phenotypic traits that predispose or protect individuals to disease. The availability of large amounts of genome wide association data across varied traits affords the opportunity to investigate the relationship between myriad traits and AD. Mendelian randomization \(MR\), the gold standard for causality in genetic studies, is a statistical approach that uses genetic data in the form of SNPs to study if an exposure exerts a casual effect in an outcome. By using Two-sample MR randomization, we have created a new platform for the AD research community that can be used to assess evidence of causality where observational associations exist.

We explore causal relationships between 298 GWASes across multiple phenotypes versus the International Genomics of Alzheimer's Project \(IGAP\). This unbiased approach greatly simplifies the implementation of MR by a simple lookup. For each phenotype, the association with AD was assessed using the inverse variance weighted \(IVW\), MR Egger, Weighted Median, and Weighted Mode methods. Here, we have applied the following inclusion criteria; genome-wide associated SNPs with a minimum p-value less than 5.0x10-8; SNPs or their proxies \(minimum R2 value = 0.8\) present in both the exposure and outcome \(AD\) datasets; R2 clumping threshold = 0.001.

![](.gitbook/assets/tu-pian%20%284%29.png)

A directed acyclic graph representing the basic IV analysis in MR framework. In an instrumental variable \(IV\) analysis, the genetic variant is an instrument related to exposure. IV needs to meet three assumptions: IV 1: instruments must be associated with the exposure; IV 2: instruments must affect the results only by exposure; IV 3: the instruments must not be associated with confounding factors.

