---
layout: page
title: Research
permalink: /research/
---

Genome-wide analyses of the past few years have revealed that a substantial portion of the genetic control of complex traits is exerted through the regulation of gene expression. Much of the genetic variation associated with complex traits falls outside the protein coding regions of genes. Mechanistic understanding of how this variation contributes to phenotype is lacking, but gene regulation is thought to play a major role. We develop and apply methods that fully harness gene regulation within complex trait association and prediction studies. 

## Genetic Architecture of Gene Expression

We performed a systematic survey of the heritability and the distribution of effect sizes across all representative tissues in the human body. Bayesian Sparse Linear Mixed Model (BSLMM) analysis provides strong evidence that the genetic contribution to local expression traits is dominated by a handful of genetic variants rather than by the collective contribution of a large number of variants each of modest size. In other words, the local architecture of gene expression traits is sparse rather than polygenic across all 40 tissues (from [DGN](http://dags.stanford.edu/dgn/) and [GTEx](https://www.gtexportal.org/home/)) examined. For most genes BSLMM PVE (percent variance explained) estimates are larger than LMM estimates reflecting the fact that BSLMM yields better estimates of heritability because of its ability to account for the sparse component. This result is confirmed by the sparsity of optimal performing gene expression predictors via elastic net modeling. See our article in [*PLOS Genetics*](https://www.ncbi.nlm.nih.gov/pubmed/?term=PMC5106030) for more information.

![GenArchFig4]({{ site.baseurl }}/images/Fig4-GTEx_TW_PVE_v_h2.jpg)

## PrediXcan

We have developed a gene-based association method called PrediXcan (pronounced "predict-scan") that directly tests the molecular mechanisms through which genetic variation affects phenotype (published in <a href="https://www.ncbi.nlm.nih.gov/pubmed/?term=PMC4552594"><i>Nature Genetics</i></a>). The approach estimates the component of gene expression determined by an individual’s genetic profile and correlates the “imputed” gene expression with the phenotype under investigation to identify genes associated with the phenotype. The genetically regulated gene expression is estimated using whole-genome tissue-dependent prediction models trained with reference transcriptome datasets. The PrediXcan novel gene-based test is focused on the mechanism of gene regulation and comes with key information on direction of effect (i.e. whether high or low gene expression is associated with disease risk). Directional information can help to close in on potential drug targets.

![PredXFig2]({{ site.baseurl }}/images/Fig2-PrediXcan-Framework.jpg)

## OmicKriging

We have developed a novel systems approach to complex trait prediction, which leverages and integrates similarity in genetic, transcriptomic or other omics-level data. Our method called OmicKriging emphasizes the use of a wide variety of systems-level data, such as those increasingly made available by comprehensive surveys of the genome, transcriptome and epigenome, for complex trait prediction. For example, integrating different omic correlation matrices such as a genetic relationship matrix (GRM) derived from SNPs and a gene expression correlation matrix (GXM) derived from gene expression levels may optimize predictive performance over either dataset alone. See our article in <a href="http://www.ncbi.nlm.nih.gov/pubmed/?term=PMC4072756"><i>Genetic Epidemiology</i></a> for more details.

![OKFig2]({{ site.baseurl }}/images/OKFig2.jpg)



## Funding and Collaborations
**R15 HG009569** 05/01/17 – 04/30/20

*Predicting Gene Regulation Across Populations to Understand Mechanisms Underlying Complex Traits*

Our project will lead to a better understanding of the effect and impact of genetic variation on gene expression and complex traits across populations, which has the potential to improve the implementation of precision medicine among diverse populations and reduce health disparities.

Role: PI
<br>
<br>
<br>
**R01 MH107666** 08/21/15 – 06/30/18
*Predicted Gene Expression: High Power, Mechanism, and Direction of Effect*The goal of this project is to develop and apply methods that fully harness gene regulation within complex psychiatric trait association and prediction studies. Role: Co-investigator (PI: <a href="https://imlab.uchicago.edu/" target="_blank">Hae Kyung Im</a>)
<br>
<br>
<br>
**R01 CA157823** 09/25/12 – 07/31/17
  *Genetic Susceptibility and Biomarkers of Platinum-Related Toxicities*The goal of this project is to understand the biologic/genetic basis of acute/late chemotherapy-related toxicity in testicular cancer patients treated with cisplatin.Role: Co-investigator (PI: <a href="http://news.medicine.iu.edu/releases/2015/08/Lois-Travis.shtml" target="_blank">Lois Travis</a>)
<br>
<br>
<br>


