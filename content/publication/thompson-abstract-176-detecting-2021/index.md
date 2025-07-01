---
title: 'Abstract 176: Detecting Neoepitopes from Tumor RNA Sequencing Datasets'
authors:
- Drew Thompson
- Olena M. Vaske
- Arjun Rao
- Holly C. Beale
date: '2021-07-01'
publishDate: '2025-07-01T14:39:29.431260Z'
publication_types:
- article-journal
publication: '*Cancer Research*'
doi: 10.1158/1538-7445.AM2021-176
abstract: "Abstract             Epitopes are peptides that present on the surface
  of the cell and can be recognized by immune cells to initiate the immune response.
  Identification of neoepitopes -- tumor-specific, MHC-bound epitopes recognized specifically
  by T-cells -- is valuable for predicting response to immunotherapies, including
  checkpoint blockade therapies. Tumors with more neoepitopes tend to be more responsive
  to immune checkpoint therapies compared to tumors with fewer neoepitopes. ProTECT
  is a previously published computational method that uses Illumina whole genome and
  transcriptome sequencing data from tumor and matched normal tissues to identify
  neoepitopes. Tumor and normal whole genome sequencing data are used to infer a patient's
  HLA haplotypes, as well as annotate variants as either somatic or germline. While
  whole genome sequencing is comprehensive, it is quite costly and not available for
  many samples. Here we adapt ProTECT to use only tumor RNA sequencing data and HLA
  haplotype information available to the clinician to identify neoepitopes in a tumor
  sample. Prior to running ProTECT, we use the computational tools Opossum and Platypus
  for variant calling instead of Radia (which is designed for variant calling using
  both RNA and DNA sequencing data as input). To determine which variants are somatic
  and therefore could represent tumor neoepitopes, variants found in RNA are compared
  to a panel of normals, for example the Genome Aggregation Database (gnomAD; containing
  variants from 125,748 exome sequences and 15,708 whole-genome sequences). With the
  resulting somatic variants and the HLA type, ProTECT proceeds as usual, with translation
  of variants into proteins, MHC:Peptide binding predictions and neoepitope ranking.
  We find that high quality neoepitopes are identifiable using an RNA-only approach,
  when genomic data is absent. Future work will validate the sensitivity of our method
  by benchmarking it against the original ProTECT predictions in the TCGA Prostate
  Adenocarcinoma cohort.             Citation Format: Drew Thompson, Olena M. Vaske,
  Arjun Rao, Holly C. Beale. Detecting neoepitopes from tumor RNA sequencing datasets
  [abstract]. In: Proceedings of the American Association for Cancer Research Annual
  Meeting 2021; 2021 Apr 10-15 and May 17-21. Philadelphia (PA): AACR; Cancer Res
  2021;81(13_Suppl):Abstract nr 176."
tags:
- /unread
---
