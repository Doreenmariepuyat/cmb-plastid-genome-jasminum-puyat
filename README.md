# Plastid Genome Characterization of *Jasminum nudiflorum*

**Student Name:** Puyat, Doreen Marie G.

**Course/Section:** BIO300 - B

## Chosen Genus and Species

**Genus:** *Jasminum*

**Selected Species:** *Jasminum nudiflorum*

**Family:** Oleaceae

## NCBI Accession and Source

**NCBI Accession/Version:** NC_008407.1
**Source:** NCBI Nucleotide / RefSeq
**Source Link:** https://www.ncbi.nlm.nih.gov/nuccore/NC_008407.1

The record is identified by NCBI as the complete chloroplast genome of *Jasminum nudiflorum*.

## Date Retrieved

**Genome retrieval date:** September 30, 2026

## Genome Size and Plastome Summary

The complete chloroplast genome of *Jasminum nudiflorum* is **165,121 bp** long and is reported as a **circular DNA molecule**. The FASTA analysis in Galaxy produced **one sequence record**, with a **GC content of 37.98%** and **0 gaps**.

The genome has the typical plastid organization consisting of a Large Single-Copy (LSC) region, Small Single-Copy (SSC) region, and two Inverted Repeat (IR) regions. The region sizes used in this analysis were inferred from the annotated genome. The plastome contains genes involved in photosynthesis, ATP production, electron transport, carbon fixation, transcription, and protein synthesis.

## Download and Galaxy Workflow

The complete FASTA sequence was downloaded from the NCBI record **NC_008407.1**. The FASTA file was then uploaded to my personal Galaxy account at **usegalaxy.org**. The uploaded dataset was renamed using the species name and accession, and a FASTA Statistics tool was used to obtain the basic sequence statistics.

## Galaxy History and Tools

**Galaxy History:** `Plastid_Jasminum_Puyat`

**Tool used:** FASTA Statistics

The main results were:

* Genome length: **165,121 bp**
* Number of sequences: **1**
* GC content: **37.98%**
* Gaps: **0**
* N50: **165,121 bp**
* L50: **1**

## Gene Content and Important Observations

The annotated genome contains **131 gene features**, including:

* **85 protein-coding sequences (CDS)**
* **38 tRNA genes**
* **8 rRNA genes**

The annotation also contains **23 intron features** and **44 exon features**. Several genes are duplicated in association with the inverted-repeat regions, including *rpl2*, *rpl23*, *ndhB*, *rps7*, *ycf1*, *ycf2*, and several rRNA and tRNA genes.

Important features include **rps12 trans-splicing**, **two introns in ycf3**, and **matK located within the trnK/tRNA-Lys intron**. No explicit pseudogene feature was identified in the GenBank annotation.

The associated study by Lee et al. (2007) also reported structural rearrangements and gene relocations in *Jasminum* chloroplast genomes.

## Data Sources and References

**Primary data source:**
NCBI Nucleotide / RefSeq. *Jasminum nudiflorum* chloroplast, complete genome. Accession **NC_008407.1**.

**Associated publication:**
Lee, H.-L., Jansen, R. K., Chumley, T. W., & Kim, K.-J. (2007). *Gene relocations within chloroplast genomes of Jasminum and Menodora (Oleaceae) are due to multiple, overlapping inversions*. Molecular Biology and Evolution, 24(5), 1161–1180.

**Galaxy:**
https://usegalaxy.org/u/doreenmariepuyat/h/plastid-jasminum-puyat

**NCBI Nucleotide:** https://www.ncbi.nlm.nih.gov/nuccore/?term=jasminum+chloroplast+complete+genome

**GenBank:** https://www.ncbi.nlm.nih.gov/nuccore/NC_008407.1

**Galaxy Training Network:** https://usegalaxy.org/?tool_id=toolshed.g2.bx.psu.edu%2Frepos%2Fiuc%2Ffasta_stats%2Ffasta-stats%2F2.0&version=latest

## Reproducibility

Another student can repeat this analysis by downloading the complete FASTA sequence for **NC_008407.1** from NCBI, uploading it to a Galaxy history, running a FASTA Statistics or equivalent sequence-statistics tool, and recording the genome length, sequence count, GC content, gaps, N50, and L50. The annotated NCBI record can then be used to examine the genes, tRNAs, rRNAs, introns, and duplicated features.
