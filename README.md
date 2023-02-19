# Proteomic-Data-Based-Breast-Cancer-Classification

Introduction
Breast cancer is the most common cancer in women in the United States, except for skin cancers. It is about 30% (or 1 in 3) of all new female cancers each year (American Cancer Society). As one of the more prevalent types of cancer, breast cancer has been heavilty studied on a cellular level. The use of precision medicine and gene therapy has become more common in the treatment of cancers . Precision medicine refers to the tailoring of medical treatment based on the cellular profile of a disease and the patient’s genome. Breast cancer is typically classified into five molecular subtypes, HER2, Luminal A, Luminal B, Luminal B-like and Basal-like. These molecular subtypes are typically determined by the genes that the cancer cell expresses. Molecular subtype classification is important because it leads to different standards of care and can improve treatment research. For example, Luminal A cancers tend grow more slowly than other cancers, be lower grade, and have a good prognosis, while HER2-enriched cancers tend to grow faster than luminal cancers and can have a worse prognosis, but are usually successfully treated with targeted therapy medicines aimed at the HER2 protein (Sheng 2022).

Background
With the prevalence of precision medicine and gene therapy, breast cancer has been studied extensively at the genomic level. Currently, the subtypes have been classified with sequencing and microarray technologies, but in recent years advances in mass spec technologies have provided deep proteome coverage and data. For example, the study in 2017, "Proteomic maps of breast cancer subtypes" found that in a comparison between proteomic data and genomic data, there is low correlation between the copy number variants in the genome and the relative change at the protein levels. This indicates that genomic variations are not translated or only partially translated to the protein level. This is important because germline copy number variations at the genomic level are associated with breast cancer risk and prognosis. Thus, it could be very useful to analyze differences of cellular function at the protein level, in additon to the genomic data to create more targeted treatment for subtype specific cancers classifications.

Objective
How is this project applicable to healthcare?
This project aims to find distinct differences in proteomic data between breast cancer molecular subtypes that could be used to further classify breast cancer into subtype-specific distinctions. More specilized and accepted classifications of breast cancer could improve treatment at the cellular level and lead to better patient prognosis and treatment.

Literature
Info about cancer prevalence https://www.cancer.org/cancer/breast-cancer/about/how-common-is-breast-cancer.html

Proteogenomics connects somatic mutations to signalling in breast cancer http://www.nature.com/nature/journal/v534/n7605/full/nature18003.html

Breast Cancer Classification Based on Proteotypes Obtained by SWATH Mass Spectrometry https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6656695/

Proteomic maps of breast cancer subtypes https://www.nature.com/articles/ncomms10259

Features Selection and Extraction in Statistical Analysis of Proteomics Datasets https://link.springer.com/protocol/10.1007/978-1-0716-1641-3_9

Info about subtypes https://www.breastcancer.org/types/molecular-subtypes

Proteogenomics connects somatic mutations to signalling in breast cancer http://www.nature.com/nature/journal/v534/n7605/full/nature18003.html

This is the original study done on the dataset used for this project. The data was used to assess how the mutations in the DNA translate to the protein expression landscape in breast cancer. Genes in our DNA are first transcribed into RNA molecules which then are translated into proteins. Changing the information content of DNA has impact on the behavior of the proteome, which is the main functional unit of cells, taking care of cell division, DNA repair, enzymatic reactions and signaling etc.

Dataset Info
This project is working with two datasets, both are obtained from https://proteomic.datacommons.cancer.gov/pdc/browse/ and contain 77 cancer patients and 3 healthy patients. One dataset contains patient clinical information and the other dataset contains proteomic data for most patients listed in the clinical dataset. The proteomic dataset contains 12,000 genes and corresponding protein ratios for each patient and clinical dataset contains the molecular subtype for breast cancer. Datasets will be combine on the patients unique IDs AO-A12D.01TCGA from proteomes and TCGA-A2-A0T2 from the clinical.

