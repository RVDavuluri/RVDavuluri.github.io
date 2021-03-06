---
title: "Davuluri Lab - Research"
layout: textlay
excerpt: "Davuluri Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

The central hypothesis of our laboratory is that the isoform-level gene products “transcript variants” and “protein isoforms” are the basic functional units in the mammalian cell, and accordingly, the informatics platforms – ranging from basic molecular biology data management systems to the biomarker and therapeutic drug target discovery for precision medicine – should adapt “gene-isoform-centric” rather than “gene-centric” approaches. 
{: style="text-align: justify"}

Our research is focused on developing statistical machine learning based algorithms and informatics solutions for knowledge extraction in biology and medicine. Our ongoing research work, funded by National Library of Medicine/NIH R01, focuses on developing novel bioinformatics methods to help in silico discovery and research for accelerating the linkage of phenotypic and genomic information at gene-isoform level. The overarching goal of the lab is to translate data from high dimensional (-omic) platforms (e.g., NextGen sequencing) to derive experimentally interpretable and testable discovery models for the identification and characterization of transcript-variants/protein isoforms, networks and pathways involved in normal and disease cells. 
{: style="text-align: justify"}

## Summary of Ongoing and Past Research Projects:

#### Viral DNABERT: A robust BERT model for SARS-Cov2 and other virus strains:
#### [Code]()
**Pratik Dutta*, Yanrong Ji**

Our group used the existing DNABERT model and science and applied it to virus strains (in collaboration with [Dr Han Liu, Department of Computer Science, Northwestern University](http://magics.cs.northwestern.edu/index.html)).
{: style="text-align: justify"}


#### DGCCA subtyping in Cancer:
#### [Code]()
**Pratik Dutta*, Zhihan Zhou**


#### DNABERT: A BERT-based model for DNA-language in genomes:
#### [Code](https://github.com/RDavuluri-Lab-SUNY-STONYBROOK/DNABERT)
**Yanrong Ji, Zhihan Zhou**

![]({{ site.url }}{{ site.baseurl }}/images/respic/dnabert.png){: style="width: 70%; float: center; margin: 10px"} 
<br/>
Understanding the hidden instructions within genome on gene regulation is crucial for biological research. However, complex language patterns widely exist in DNA, such as polysemy and distant semantic relationship, which previous methods often fail to capture especially in data-scarce scenarios. For the first time, our group (in collaboration with [Dr Han Liu, Department of Computer Science, Northwestern University](http://magics.cs.northwestern.edu/index.html)) developed **DNABERT** to enhance the global understanding of genomic sequences based on up and downstream sequence contexts. Using an innovative global contextual embedding of input sequences, DNABERT attempts to tackle the problem of sequence specificity prediction with a “top-down” approach by developing general understanding of DNA language via self-supervised pre-training and applying it to specific tasks (for example, prediction of promoters, transcription factor binding sites and splice sites), in contrast to the traditional “bottom-up” approach using task-specific data. Various modules of DNABERT are currently under development. It is anticipated that the pre-trained DNABERT on the human genome can also be readily applied to data from other organisms with exceptional performance.
{: style="text-align: justify"}
<br/>
<br/>
#### ExTraMapper: exon- and transcript-level mappings for orthologous gene pairs:
#### [Code](https://github.com/RDavuluri-Lab-SUNY-STONYBROOK/ExTraMapper)
**Abhijit Chakraborthy, Ferhat Ay**

![]({{ site.url }}{{ site.baseurl }}/images/respic/extramapper.jpeg){: style="width: 70%; float: center; margin: 10px"}
<br/>
ExTraMapper is a novel tool to find Exon and Transcript-level Mappings of a given pair of orthologous genes between two organisms leveraging sequence conservation between exons of a pair of organisms and produces a fine-scale orthology mapping at the exon and then transcript level. The tool identifies a larger number of exon and transcript mappings compared to previous methods. Further, it identifies exon fusions, splits and losses due to splice site mutations, and finds mappings between microexons that were previously missed.
{: style="text-align: justify"}
<br/>
<br/>
### Platform-independent isoform-level gene signatures for stratification of cancer patients into molecular subgroups:
**Sharmishtha Pal, Yingtao Bi, Arunima Shilpi, Yanrong Ji, Manoj Kandpal**

![]({{ site.url }}{{ site.baseurl }}/images/respic/pigex.jpg){: style="width: 70%; float: center; margin: 10px"}<br/>
Based on recent studies from Our group and others, significant expression differences were observed between different sample groups (e.g., developmental stages, cancer subtypes, normal vs cancer) for numerous genes at the isoform-level but not at the overall gene-level. We investigated whether the isoform-level transcriptome changes could provide better patient stratification in terms of overall prognosis and classification accuracy. His group developed novel methods, by integrating data discretization, feature selection, and meta-classification algorithms, for derivation of platform-independent gene signature for multi-label molecular stratification of cancer patients, from exon-array and RNA-seq data. The application of these algorithms has led to the development of new methods for diagnosis of glioblastoma and ovarian serous carcinoma among others, and the investigation of alternative splicing on drug-target gene interactions.
{: style="text-align: justify"}
<br/>
<br/>
### Isoform-level gene expression and regulation in mammalian development and cancer:
Recent genome-wide studies have discovered that majority of human genes produce multiple transcript-variants/protein-isoforms, which could be involved in different functional pathways. Moreover, altered expression of specific isoforms for numerous genes is linked with cancer and its prognosis, as cancer cells manipulate regulatory mechanisms to express specific isoforms that confer drug resistance and survival advantages. For example, cancer-associated alterations in alternative exons and splicing machinery have been identified in cancer samples, suggesting that specific transcript-variants could be more effective as diagnostic and prognostic markers than corresponding genes. In a recent study, Our Dgroup discovered that majority of genes associated with neurological diseases expressed multiple transcripts through alternative promoters by using integrative NextGen sequencing based experimental approaches and bioinformatics analysis. The study also observed aberrant use of alternative promoters and splice variants in different cancers. Subsequently, his group demonstrated that cancer cell-lines regardless of their tissue of origin can be effectively discriminated from non-cancer cell-lines at isoform-level, but not at gene-level. The novel informatics methods have been successfully applied by his collaborators in different cancer studies.
{: style="text-align: justify"}
<br/>
<br/>
### Algorithms and bioinformatics software for analyses of NextGen sequence data:
Mapping genome-wide data to human subtelomeres has been problematic due to the incomplete assembly and challenges of lowcopy repetitive DNA elements. Our group developed novel bioinformatics pipelines for incorporating multi-read mapping for annotation of the updated assemblies using short-read data sets from ChIP-seq data, and RNA-seq data. As part of other collaborative efforts, we also developed bioinformatics methods for identification of single-nucleotide polymorphisms (SNPs) that alter miRNA gene regulation and influence tumor susceptibility. 
{: style="text-align: justify"}
<br/>
<br/>
![]({{ site.url }}{{ site.baseurl }}/images/respic/SmartTip.png){: style="width: 250px; float: left; margin: 0px  10px"}


