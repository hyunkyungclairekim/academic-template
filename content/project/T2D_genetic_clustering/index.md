---
title: Genetic Clustering of Type 2 Diabetes
summary: Inferring genetic pathways of Type 2 Diabetes using a soft clustering approach 
tags:
- Type 2 Diabetes
- Soft clustering
- Variant trait association
date: "2020-06-1T00:00:00Z"

# {{< figure src="T2D_genetic_clustering_9clusters.png" title="9 Clusters of T2D loci and related traits" >}}


# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Beta-cell1 cluster identified by clustering analysis
  focal_point: Smart
  preview_only: false


links:
- name: Link
  url: https://diabetes.diabetesjournals.org/content/69/Supplement_1/1644-P
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---


## Abstract
</br>

Improved understanding of disease-causing pathways for type 2 diabetes (T2D) may lead to novel therapeutic targets and individualized treatment. Rapid expansion in the number of T2D genetic loci over the past few years can be leveraged to identify pathways via cluster analysis.

We developed an automated pipeline to enable clustering of T2D genetic loci starting with genome-wide association study (GWAS) summary statistics from 6 European T2D studies. The pipeline 1) extracts variants reaching genome-wide significance, 2) replaces multi-allelic, ambiguous (A/T, C/G), or low-trait count SNPs with appropriate proxies, and 3) filters for independent signals using r2=0. Traits in the T2D Knowledge Portal with summary GWAS data in European populations were included if they met a minimum Bonferroni p-value across the selected variants. This pipeline generated a matrix of associations for 259 independent T2D variants and 32 traits to which we applied Bayesian Non-negative Matrix Factorization (bNMF) clustering.

We identified 6 robust clusters of T2D loci, 5 of which overlapped with a previously published analysis of 94 loci. Three clusters indicated variant-trait associations related to insulin deficiency, while the other three clusters displayed insulin resistance-related features including: obesity, lipodystrophy, and liver-lipid metabolism. The new cluster identified in this analysis is related to beta cell function. Increased polygenic scores for clusters were associated with distinct clinical outcomes in GWAS, including coronary artery disease (UK BioBank CARDIoGRAM), ischemic stroke (MEGASTROKE), chronic kidney disease (CKDGen). Clusters also displayed tissue-specific epigenomic enrichment.

Our approach expands upon previous clustering work of T2D loci and allows for efficient updating as additional GWAS results become available. This method can also be readily applied to other diseases beyond T2D to identify key pathways.
