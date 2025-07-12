+++
author = "Anlin Feng"
title = "The workflow for single-cell RNA sequencing analysis"
date = "2025-07-12"
description = "A brief introduction of single-cell RNA-sequencing"
image = "bioinfor.png"
tags = [
    "papers",
    "science",
    "tech"
]
math = true
+++

## Experimental Procedure of scRNA-seq
Single-cell RNA sequencing (scRNA-seq) technology, pioneered by Tang et al. in 2009, offers a novel approach to elucidating the heterogeneity of RNA transcripts within individual cells. Furthermore, it enables the identification of the composition of distinct cell types and their associated functions within tissues or organs across various diseases.

The scRNA-seq technology sequenced the transcriptome of single cells, opening a new avenue to scale up the number of cells and merging high-throughput RNA sequencing technology. By skipping all wet lab steps used in scRNA-seq, we directly proceed to generating single-cell-barcoded cDNAs from single cells or single nuclei. Subsequently, the cDNA can be sequenced using various deep sequencing platforms. Currently, popular platforms include 10x Genomics Chromium, Fluidigm C1, Drop-seq, and Smart-seq2.

## Data Preprocessing
The fundamental formats of raw sequencing data obtained from sequencing platforms, such as FASTQ and BCL formats, are utilized for single-cell transcriptome analysis. These formats are dependent on the data source and sequencing platform. Since only FASTQ files can be directly employed for quality control, the initial step in processing raw data is to convert them to FASTQ format using appropriate tools.
