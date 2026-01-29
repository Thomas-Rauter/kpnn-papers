# Knowledge-Primed Neural Networks

This repository provides a curated list of publications on **Knowledge-Primed Neural Networks (KPNNs)**, with short summaries and links.

Note that in the literature also other names are used for the same concept, such as Visible Neural Networks (VNN), knowledge-guided neural networks, knowledge-based neural networks, ontology-based autoencoders, and biologically informed neural networks (BINNs). In the remainder of this repository, we use the term KPNN to collectively refer to all of these closely related approaches.

## What are KPNNs?

KPNNs are a method in biological modelling and are artificial neural networks whose architecture is explicitly informed by a prior knowledge network, such as biological pathways or ontology networks. Network nodes correspond to nodes of the prior knowledge network, enabling a direct mapping between model components and domain concepts.

By combining this architecture with attribution methods, individual nodes can be ranked according to their contribution to the prediction task, which corresponds to their importance in the prior knowledge network. This makes model predictions interpretable, leading to scientific insights.

![KPNN overview © 2026 Thomas Rauter. All rights reserved. KPNNs based on a biological network (left) have first been published by [Bock, 2020](https://doi.org/10.1186/s13059-020-02100-5) and KPNNs based on an ontology network have first been published by [Hahn & Van Allen, 2021](https://doi.org/10.1038/s41586-021-03922-4).](kpnns_explained.svg)

## Literature Overview

Over the past years, a growing number of high-impact publications have explored Knowledge-Primed Neural Networks across multiple domains. Below is a curated list of representative papers in this research direction, organized by application field.

-   [**Han, 2025**](https://doi.org/10.1186/s13073-025-01584-9) ![Article](https://img.shields.io/badge/type-article-blue)\
    *PathHDNN: a pathway hierarchical-informed deep neural network framework for predicting immunotherapy response and mechanism interpretation*. Genome Medicine.
    
-   [**Pickering, 2025**](https://doi.org/10.48550/arXiv.2510.14970) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Biology-informed neural networks learn nonlinear representations from omics data to improve genomic prediction and interpretability*. arXiv.
    
-   [**Huang, 2025**](10.1016/j.csbj.2025.10.063) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Pathway-guided architectures for interpretable AI in biological research*. Computational and Structural Biotechnology Journal.

-   [**Nilson, 2025**](https://doi.org/10.1101/2025.10.24.684155) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Biologically informed neural network models are robust to spurious interactions via self-pruning*. bioRxiv.

-   [**Vollmer, 2025**](https://doi.org/10.3389/frai.2025.1595291) ![Review](https://img.shields.io/badge/type-review-green)\
    *Visible neural networks for multi-omics integration: a critical review*. Frontiers in Artificial Intelligence.

-   [**Vollmer, 2025**](https://doi.org/10.1038/s41576-025-00826-1) ![Commentary](https://img.shields.io/badge/type-commentary-lightgrey)\
    *Beyond the black box with biologically informed neural networks*. Nature Reviews Genetics.
    
-   [**Chen, 2024**](https://doi.org/10.1093/bib/bbae384) ![Article](https://img.shields.io/badge/type-article-blue)\
    *BioM2: biologically informed multi-stage machine learning for phenotype prediction using omics data*. Briefings in Bioinformatics.
    
-   [**Yachie, 2024**](10.2131/jts.49.105) ![Article](https://img.shields.io/badge/type-article-blue)\
    *DTox: A deep neural network-based in visio lens for large scale toxicogenomics data*. The Journal of Toxicological Sciences.
    
-   [**Chen, 2024**](https://doi.org/10.1093/bib/bbae185) ![Article](https://img.shields.io/badge/type-article-blue)\
    *DeepKEGG: a multi-omics data integration framework with biological insights for cancer recurrence prediction and biomarker discovery*. Briefings in Bioinformatics.
    
-   [**Heinemann, 2024**](10.1109/SDS60720.2024.00044) ![Article](https://img.shields.io/badge/type-article-blue)\
    *DeepBINN: A tailored biologically-informed neural network for robust biomarker identification*. 2024 11th IEEE Swiss Conference on Data Science (SDS).
    
-   [**Wu, 2023**](10.1186/s12859-023-05535-2) ![Article](https://img.shields.io/badge/type-article-blue)\
    *PathExpSurv: pathway expansion for explainable survival analysis and disease gene discovery*. BMC Bioinformatics.

-   [**Ceccarelli, 2023**](https://doi.org/10.1093/bioinformatics/btad432) ![Article](https://img.shields.io/badge/type-article-blue)\
    *MOViDA: multiomics visible drug activity prediction with a biologically informed neural network model*. Bioinformatics.
    
-   [**Cicek, 2023**](https://doi.org/10.1093/bioinformatics/btad684) ![Article](https://img.shields.io/badge/type-article-blue)\
    *PiDeeL: metabolic pathway-informed deep learning model for survival analysis and pathological classification of gliomas*. Bioinformatics.
    
-   [**Lee, 2023**](https://doi.org/10.3389/fnagi.2023.1126156) ![Article](https://img.shields.io/badge/type-article-blue)\
    *PINNet: a deep neural network with pathway prior knowledge for Alzheimer's disease*. Frontiers in Aging Neuroscience.

-   [**Fortelny, 2023**](https://doi.org/10.1038/s41540-023-00310-8) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Reliable interpretability of biology-inspired deep neural networks*. Systems Biology and Applications.

-   [**Freitas, 2023**](https://doi.org/10.1186/s12859-023-05262-8) ![Review](https://img.shields.io/badge/type-review-green)\
    *A systematic review of biologically-informed deep learning models for cancer: fundamental trends for encoding and interpreting oncology data*. BMC Bioinformatics.
    
-   [**Chen, 2023**](10.1093/bib/bbad449) ![Article](https://img.shields.io/badge/type-article-blue)\
    *CellTICS: an explainable neural network for cell-type identification and interpretation based on single-cell RNA-seq data*. Briefings in Bioinformatics.
    
-   [**Freitas, 2023**](10.1186/s12859-023-05262-8) ![Review](https://img.shields.io/badge/type-review-green)\
    *A systematic review of biologically-informed deep learning models for cancer: fundamental trends for encoding and interpreting oncology data*. BMC Bioinformatics.
    
-   [**Loucera, 2023**](10.3390/biology12040579) ![Article](https://img.shields.io/badge/type-article-blue)\
    *SigPrimedNet: A Signaling-Informed Neural Network for scRNA-seq Annotation of Known and Unknown Cell Types*. Biology.
    
-   [**Wang, 2023**](10.1186/s13073-023-01248-6) ![Article](https://img.shields.io/badge/type-article-blue)\
    *DeepGAMI: deep biologically guided auxiliary learning for multimodal integration and imputation to improve genotype-phenotype prediction*. Journal.

-   [**Lauffenburger, 2022**](https://doi.org/10.1038/s41467-022-30684-y) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Artificial neural networks enable genome-scale simulations of intracellular signaling*. Nature Communications.
    
-   [**Park, 2022**](https://doi.org/10.1093/bib/bbac171) ![Article](https://img.shields.io/badge/type-article-blue)\
    *DeepHisCoM: deep learning pathway analysis using hierarchical structural component models*. Briefings in Bioinformatics.

-   [**Hanczar, 2022**](https://doi.org/10.1093/bioinformatics/btac147) ![Article](https://img.shields.io/badge/type-article-blue)\
    *GraphGONet: a self-explaining neural network encapsulating the Gene Ontology graph for phenotype prediction on gene expression*. Bioinformatics.

-   [**Mostafavi, 2022**](https://doi.org/10.1038/s41576-022-00532-2) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Obtaining genetics insights from deep learning via explainable artificial intelligence*. Nature Reviews Genetics.

-   [**He, 2022**](https://doi.org/10.1093/bioinformatics/btac636) ![Article](https://img.shields.io/badge/type-article-blue)\
    *MPVNN: Mutated Pathway Visible Neural Network for interpretable prediction of cancer survival*. Bioinformatics.

-   [**Moore, 2022**](https://doi.org/10.1016/j.patter.2022.100565) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Knowledge-guided deep learning models of drug toxicity improve interpretation*. Patterns.
    
-   [**Wang, 2021**](https://doi.org/10.1093/nargab/lqab097) ![Article](https://img.shields.io/badge/type-article-blue)\
    *ParsVNN: parsimony visible neural networks for uncovering cancer-specific and drug-sensitive genes and pathways*. NAR Genomics and Bioinformatics.
    
-   [**Roshchupkin, 2021**](https://doi.org/10.1038/s42003-021-02622-z) ![Article](https://img.shields.io/badge/type-article-blue)\
    *GenNet framework: interpretable deep learning for predicting phenotypes from genetic data*. Communications Biology.

-   [**Hahn & Van Allen, 2021**](https://doi.org/10.1038/s41586-021-03922-4) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Biologically informed deep neural network for prostate cancer discovery*. Nature.
    
-   [**Lichtarge, 2021**](https://doi.org/10.1093/bioinformatics/btab137) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Using interpretable deep learning to model cancer dependencies*. Bioinformatics.
    
-   [**Zhao, 2021**](10.1016/j.csbj.2021.04.067) ![Article](https://img.shields.io/badge/type-article-blue)\
    *DeepOmix: A scalable and interpretable multi-omics deep learning framework and application in cancer survival analysis*. Computational and Structural Biotechnology Journal.
    
-   [**Ahn, 2021**](10.3390/ijms222111531) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Classification and Functional Analysis between Cancer and Normal Tissues Using Explainable Pathway Deep Learning through RNA-Sequencing Gene Expression*. International Journal of Molecular Sciences.

-   [**Kohandel, 2021**](https://doi.org/10.1038/s42003-021-02393-7) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Systems biology informed neural networks predict response to PD-1 checkpoint blockade*. Communications Biology.
    
-   [**Hanczar, 2021**](10.1186/s12859-021-04370-7) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Deep GONet: self-explainable deep neural network based on Gene Ontology for phenotype prediction from gene expression data*. BMC Bioinformatics.

-   [**Bock, 2020**](https://doi.org/10.1186/s13059-020-02100-5) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Knowledge-primed neural networks enable biologically interpretable deep learning on single-cell sequencing data*. Genome Biology.
    
-   [**Kang, 2020**](https://doi.org/10.1142/9789811215636_0032) ![Article](https://img.shields.io/badge/type-article-blue)\
    *PAGE-Net: Interpretable and Integrative Deep Learning for Survival Analysis Using Histopathological Images and Genomic Data*. Pacific Symposium on Biocomputing.

-   [**Ideker, 2020**](10.1016/j.ccell.2020.09.014) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Predicting Drug Response and Synergy Using a Deep Learning Model of Human Cancer Cells*. Cancer Cell.
    
-   [**Liu, 2020**](10.1021/acs.jcim.0c00331) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Pathway-Guided Deep Neural Network toward Interpretable and Predictive Modeling of Drug Sensitivity*. Journal of Chemical Information and Modeling.

-   [**Gerstein, 2018**](10.1126/science.aat8464) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Comprehensive functional genomic resource and integrative model for the human brain*. Science.

-   [**Ideker, 2018**](https://doi.org/10.1038/nmeth.4627) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Using deep learning to model the hierarchical structure and function of a cell*. Nature Methods.

-   [**Kang, 2018**](https://doi.org/10.1186/s12859-018-2500-z) ![Article](https://img.shields.io/badge/type-article-blue)\
    *PASNet: pathway-associated sparse deep neural network for prognosis prediction from high-throughput data*. BMC Bioinformatics.

-   [**Kang, 2018**](https://doi.org/10.1109/BIBM.2018.8621345) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Cox-PASNet: pathway-based sparse deep neural network for survival analysis*. IEEE BIBM.

## Contributions and feedback

This list is intended to be a curated and evolving overview of publications on knowledge-primed, visible, and biologically informed neural network architectures.\
If you believe that a publication should be included in this list, that an included publication does not fit the scope, or that any information has been recorded incorrectly, please open an issue and provide a short justification or reference.

Constructive feedback and corrections are very welcome.



-   [**Last_author, year**](DOI) ![Article](https://img.shields.io/badge/type-article-blue)\
    *Title*. Journal.
