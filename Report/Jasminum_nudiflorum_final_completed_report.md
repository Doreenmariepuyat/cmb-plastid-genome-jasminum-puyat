# Cell & Molecular Biology Lab Activity: Characterization of a Plastid Genome

**Name:** Puyat, Doreen Marie G.

**Course:** BIO300- Cell and Molecular Biology

**Section:** B

# 1. Purpose

In this activity, one plant genus with an available complete plastid genome was selected. A complete plastid/chloroplast genome was retrieved from a public database, uploaded to usegalaxy.org, characterized using sequence statistics and genome annotation, and documented in a GitHub repository.

# 2. Learning Outcomes

- Locate and verify a complete plastid/chloroplast genome in NCBI.
- Explain basic plastid-genome terms such as LSC, SSC, IR, CDS, rRNA, tRNA, intron, pseudogene, and GC content.
- Describe the overall organization and gene content of a selected plastid genome.
- Use Galaxy to upload a plastid genome and obtain basic sequence statistics.
- Compare plastid genomes with mitochondrial and nuclear genomes.
- Evaluate practical advantages and limitations of plastid genomes in biological studies.
- Document the data source, analysis steps, results, and interpretation in GitHub.

  
# 3. Choosing and Recording a Plant Genus

**Chosen genus:** *Jasminum*

**Selected species:** *Jasminum nudiflorum*

**Common name:** Winter jasmine

**Family:** Oleaceae

**Organelle:** Chloroplast (plastid)

**NCBI accession:** NC_008407.1

<img width="429" height="123" alt="image" src="https://github.com/user-attachments/assets/19595345-7708-4dc8-9b68-c1f142f0d2e3" />

**Figure 1.** NCBI record for the *Jasminum nudiflorum* chloroplast complete genome (NC_008407.1), showing the 165,121 bp genome length, circular topology, and associated publication information.

<img width="1206" height="646" alt="image" src="https://github.com/user-attachments/assets/712fcae0-d760-4262-b17d-f9f88826a4f8" />

**Figure 2.** FASTA sequence record of the selected *Jasminum nudiflorum* chloroplast complete genome (NC_008407.1) retrieved from NCBI and used as the genome sequence source for the Galaxy analysis.

# 4. Data Source and Genome Selection

| Item | Information |
|---|---|
| Chosen genus | Jasminum |
| Selected species | Jasminum nudiflorum |
| Common name | Winter jasmine |
| Family | Oleaceae |
| Organelle | Chloroplast (plastid) |
| Genome type | Complete chloroplast genome |
| NCBI accession/version | NC_008407.1 |
| Database | NCBI RefSeq / Nucleotide |
| Genome length | 165,121 bp |
| Topology | Circular |
| Sequence status | Complete genome |
| Source | NCBI Nucleotide / RefSeq |
| Associated publication | Lee et al. (2007), Gene relocations within chloroplast genomes of Jasminum and Menodora (Oleaceae) are due to multiple, overlapping inversions |
| NCBI record | https://www.ncbi.nlm.nih.gov/nuccore/NC_008407.1 |

# 5. Files to Obtain

| File | Format | Purpose | File/Accession |
|---|---|---|---|
| Genome sequence | FASTA | Upload to Galaxy and obtain sequence statistics | Jasminum nudiflorum chloroplast genome, NC_008407.1 |
| Annotated genome | GenBank / RefSeq | Identify genes, coordinates, introns, duplications, and other features | Jasminum nudiflorum chloroplast genome, NC_008407.1 |
| Source information | NCBI record / accession | Document the origin of the genome used | NC_008407.1 — NCBI Nucleotide |

# 6. Galaxy Workflow

The FASTA file for NC_008407.1 was downloaded from NCBI and uploaded to the personal Galaxy history. The **FASTA Statistics** tool was then used to determine the basic sequence characteristics.

| Statistic | Galaxy Result |
|---|---:|
| Genome length | 165,121 bp |
| Number of sequence records | 1 |
| GC content | 37.98% |
| Gaps | 0 |
| Complete plastome represented by one sequence | Yes |
| N50 | 165,121 bp |
| L50 | 1 |

<img width="1360" height="639" alt="image" src="https://github.com/user-attachments/assets/bd124174-f983-4b10-a9c2-24ad1350d19e" />

**Figure 3.** Galaxy FASTA Statistics result for the *Jasminum nudiflorum* chloroplast genome. The uploaded FASTA contains one sequence with a total length of 165,121 bp, 37.98% GC content, and no gaps.


**Interpretation:** The Galaxy result contains one continuous sequence with a length that matches the NCBI record. The single sequence record, zero gaps, and complete-genome NCBI annotation are consistent with a complete plastome.

# 7. Plastid Genome Terms to Understand

| Term | Meaning |
|---|---|
| Plastid genome / plastome | The DNA found inside a plastid. In green plants, this usually refers to chloroplast DNA. |
| LSC | Stands for Large Single-Copy region. It is one of the main regions of the plastid genome. |
| SSC | Stands for Small Single-Copy region. It is another main region of the plastid genome. |
| IR | Stands for Inverted Repeat region. Many plastid genomes have two copies of this region. |
| CDS | Means protein-coding sequence. It is a DNA sequence that contains information for making a protein. |
| tRNA gene | A gene that produces transfer RNA, which is involved in protein production. |
| rRNA gene | A gene that produces ribosomal RNA, which is part of the plastid ribosome. |
| Intron | A non-coding part of a gene that is removed from the RNA during RNA processing. |
| Pseudogene | A gene-like sequence that has lost, or may have lost, its normal function. |
| GC content | The percentage of guanine (G) and cytosine (C) bases in the genome. |
| Accession | A unique identification number given to a sequence record in a database. |
| Annotation | Information added to a genome that identifies genes and other important features. |

# 8. Required Plastid Genome Characterization

| Characteristic | Jasminum nudiflorum chloroplast genome |
|---|---|
| Genus | Jasminum |
| Species | Jasminum nudiflorum |
| Family | Oleaceae |
| NCBI accession/version | NC_008407.1 |
| Genome size | 165,121 bp |
| GC content | 37.98% |
| Topology | Circular |
| LSC size | 92,877 bp |
| SSC size | 13,272 bp |
| IR size | 29,486 bp each |
| Number of sequence records | 1 |
| Total annotated genes | 133 genes reported in the original complete-genome study |
| Current GenBank gene features | 131 gene features in the current NC_008407.1 annotation |
| Protein-coding features (CDS) | 85 in the current annotation |
| tRNA features | 38 in the current annotation |
| rRNA features | 8 in the current annotation |
| Introns | 23 annotated intron features in the current annotation |
| Pseudogenes | No explicit pseudogene feature identified in the current GenBank annotation |
| Gene duplications | Several genes occur in two copies, especially genes associated with the IRs; ycf1 is duplicated through IR expansion |
| Overall organization | LSC–IR–SSC–IR |

## Gene Groups Identified

| Gene group | Examples / what to look for | Main function |
|---|---|---|
| psa | psaA and other psa genes | Involved in Photosystem I and photosynthesis. |
| psb | psbA and other psb genes | Involved in Photosystem II and photosynthesis. |
| atp | atpA, atpF, and other atp genes | Encode components of ATP synthase, which helps produce ATP. |
| pet | petB, petD, petN, and other pet genes | Encode components of the cytochrome b6f complex involved in electron transport. |
| rbcL | rbcL | Encodes the large subunit of RuBisCO, which is involved in carbon fixation. |
| rpo | rpoA, rpoC1, and other rpo genes | Encode RNA polymerase components used in transcription. |
| rpl | rpl2, rpl16, rpl23, and other rpl genes | Encode ribosomal proteins of the large ribosomal subunit. |
| rps | rps7, rps12, rps16, and other rps genes | Encode ribosomal proteins of the small ribosomal subunit. |
| rrn | rrn16, rrn23, rrn4.5, rrn5 | Encode ribosomal RNA. |
| trn | trn / tRNA genes | Encode transfer RNAs used during protein synthesis. |
| matK | matK | Encodes maturase K, involved in RNA processing and splicing. |
| clpP | clpP | Encodes a protease component involved in protein processing/degradation. |
| accD | accD region/gene | Associated with fatty-acid biosynthesis; the J. nudiflorum genome is notable for extensive reduction/loss of accD sequences. |
| cemA | cemA | Conserved chloroplast envelope membrane-associated gene. |
| ycf | ycf1, ycf2, ycf3, ycf genes | Conserved chloroplast genes with diverse or incompletely characterized functions. |

<img width="1235" height="635" alt="image" src="https://github.com/user-attachments/assets/90d0b801-55fd-422a-992f-d49ae9aca3a1" />

**Figure 4.** NCBI RefSeq record used for the plastid genome characterization of *Jasminum nudiflorum*, showing accession NC_008407.1, genome size of 165,121 bp, circular topology, and annotated genomic information.

# 9. Questions for the Student Report

## 1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.

My selected organism is *Jasminum nudiflorum*, commonly known as winter jasmine. It belongs to the family Oleaceae. The complete chloroplast genome was obtained from the NCBI RefSeq/Nucleotide database with accession NC_008407.1. The genome has a total length of 165,121 bp and is represented as circular DNA.

## 2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?

The NCBI record is specifically named *Jasminum nudiflorum* chloroplast, complete genome and has the RefSeq accession NC_008407.1. The sequence is 165,121 bp long and contains numerous annotated chloroplast genes, including protein-coding genes, tRNA genes, and rRNA genes. The Galaxy FASTA Statistics result also shows one sequence with the same total length of 165,121 bp. Together, these features support that the selected sequence is a complete chloroplast genome rather than a short barcode marker or isolated genome fragment.

## 3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.

Yes. The *Jasminum nudiflorum* chloroplast genome has the LSC–IR–SSC–IR organization. The complete-genome study reported:

- **LSC:** 92,877 bp
- **SSC:** 13,272 bp
- **IRa:** 29,486 bp
- **IRb:** 29,486 bp

The two IR regions separate the LSC and SSC regions. The unusually large IRs are associated with expansion and duplication of genes such as ycf1.

## 4. Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.

The original complete-genome study reported 133 genes in the *J. nudiflorum* chloroplast genome. In the current NC_008407.1 GenBank annotation used for this analysis, there are 131 gene features, including 85 CDS features, 38 tRNA features, and 8 rRNA features.

Genes located inside an inverted-repeat region can appear in two copies because the IR occurs twice in the circular plastid genome. In *J. nudiflorum*, expansion of the IR has also resulted in duplication of ycf1, which is normally a single-copy gene in many plastid genomes.

The current annotation does not contain an explicit pseudogene feature. However, the published study discusses gene reduction and gene fragments, including extensive reduction of accD.

## 5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.

| Gene | Functional Group | Function |
|---|---|---|
| rbcL | Photosynthesis / carbon fixation | Encodes the large subunit of RuBisCO, which participates in carbon fixation. |
| psaA | Photosystem I | Encodes a core Photosystem I protein involved in the light reactions of photosynthesis. |
| psbA | Photosystem II | Encodes the D1 protein of Photosystem II, an important component of the photosynthetic reaction center. |
| atpA | ATP production | Encodes the alpha subunit of ATP synthase, which participates in ATP production. |
| petB | Electron transport | Encodes a component of the cytochrome b6f complex involved in photosynthetic electron transport. |
| rpoA | Transcription | Encodes a subunit of the plastid-encoded RNA polymerase. |
| rpl16 | Translation | Encodes a ribosomal protein of the large ribosomal subunit. |
| matK | RNA processing | Encodes maturase K, which is involved in processing and splicing of chloroplast RNAs. |

## 6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.

The current annotation contains 8 rRNA features, including rrn16, rrn23, rrn4.5, and rrn5, with the rRNA genes duplicated in the IR regions.

Examples of tRNA genes include tRNA-Lys (UUU), tRNA-Gly (UCC), tRNA-Leu (UAA), tRNA-Val (UAC), tRNA-Ile (GAU), and tRNA-Ala (UGC).

Several genes contain introns. Examples include rps16, atpF, rpoC1, rpl16, rpl2, ndhB, ndhA, petB, petD, and ycf3. The annotation contains 23 intron features. Notably, ycf3 contains two introns, and rps12 is annotated as a trans-spliced gene. The matK gene occurs within the intron of the tRNA-Lys (UUU) gene.

## 7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.

The *J. nudiflorum* chloroplast genome has several unusual structural features. The 2007 study reported multiple overlapping inversions, gene duplications, insertions, IR expansion, and gene and intron losses. A 2.8-kb region containing ycf4 and psaI was relocated to the middle of the LSC region through two overlapping inversions. The study also reported duplication of ycf1 caused by IR expansion and a reduction of the accD region.

Two introns normally found in clpP are absent in *J. nudiflorum*. The study also described highly repeated sequences associated with the reduced accD region and downstream of clpP. These features make the genome organization of *Jasminum* different from the more conserved chloroplast genome arrangement seen in many other flowering plants.

The current GenBank annotation does not contain an explicit `pseudogene` feature, so a pseudogene should not be claimed solely from the annotation.

## 8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.

The GC content of the *Jasminum nudiflorum* chloroplast genome is 37.98%, based on the Galaxy FASTA Statistics result.

Two notable observations are:

1. The genome is represented by one sequence record with a total length of 165,121 bp, matching the NCBI record.
2. The chloroplast genome has an LSC–IR–SSC–IR structure with unusually large 29,486-bp IRs. The IR expansion includes duplication of ycf1 and contributes to the distinctive organization of the *J. nudiflorum* plastome.

The published study also reported an overall A–T content of approximately 62%, indicating that the genome is AT-rich.

## 9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| Location | Found inside plastids, such as chloroplasts. | Found inside mitochondria. |
| Main role | Mainly involved in photosynthesis, carbon fixation, and other plastid functions. | Mainly involved in cellular respiration and energy-related functions. |
| DNA | Contains its own DNA. | Contains its own DNA. |
| Inheritance | Often inherited from one parent in plants, commonly the maternal parent in many lineages, but exceptions exist. | Often inherited from one parent in plants, commonly maternal, but inheritance varies among organisms. |
| Copy number | Multiple copies of plastid DNA can occur in cells and chloroplasts. | Multiple copies of mitochondrial DNA can occur in cells and mitochondria. |
| Genome organization | Plant plastid genomes commonly have LSC, SSC, and two IR regions. | Plant mitochondrial genomes have much more variable physical organization and can contain repeats and recombined structures. |
| Gene content | Contains genes related to photosynthesis, transcription, translation, RNA processing, and other plastid functions. | Contains genes mainly associated with mitochondrial respiration and other mitochondrial functions. |
| Evolution | Can undergo gene loss, gene transfer, inversions, duplications, and other rearrangements. | Can also undergo gene loss, gene transfer, recombination, and structural changes, often with greater structural variability in plants. |

### Similarities

1. Both are organelle genomes.
2. Both contain their own DNA.
3. Both can occur in multiple copies per cell.
4. Both contain genes required for organelle functions.
5. Both have evolutionary histories associated with bacterial endosymbiosis.

### Differences

1. Plastid genomes are located in plastids, whereas mitochondrial genomes are located in mitochondria.
2. Plastids are strongly associated with photosynthesis and carbon fixation, whereas mitochondria are strongly associated with cellular respiration and energy metabolism.
3. Plastid genomes contain photosynthesis-related genes, while mitochondrial genomes contain genes mainly associated with mitochondrial functions.
4. Plant plastid genomes commonly have LSC, SSC, and IR regions, while plant mitochondrial genomes have much more variable organizations.
5. Plant plastid and mitochondrial genomes can differ in their inheritance patterns, mutation rates, recombination, and structural evolution.

## 10. Explain the practical value of plastid genomes in research. List as many advantages as you can compared with the nuclear genome, including nuclear sex chromosomes where applicable, and also explain important limitations. Give one research question for which plastid data would be useful and one for which nuclear genomic data would be more appropriate.

Plastid genomes are useful in many areas of plant research because they are relatively small compared with nuclear genomes and contain conserved genes and other regions that can be compared among plant species.

### Advantages of plastid genomes

- Useful for plant species identification.
- Useful for DNA barcoding.
- Useful for phylogenetic analysis.
- Useful for studying evolutionary relationships.
- Useful for comparing closely related plant species.
- Useful for studying plant diversity.
- Useful for studying population and maternal lineage history.
- Easier to analyze than the much larger nuclear genome.
- Contains conserved genes that can be compared across species.
- Useful for studying plastid evolution.
- Useful for chloroplast genetic engineering and biotechnology.
- Useful for studying photosynthesis-related genes and plastid functions.
- Less complicated than nuclear genomes for some comparative analyses because plastid genomes have relatively compact gene content.

### Limitations

Plastid genomes do not contain all of the genetic information of a plant. They represent only one organelle genome, so they cannot describe the complete genetic variation found in the nuclear genome. Plastid inheritance can also be biased toward one parent. In addition, many important plant traits are controlled by nuclear genes, so plastid DNA alone may not be sufficient to study them.

### Research question where plastid data would be useful

**What are the evolutionary relationships among *Jasminum nudiflorum* and closely related *Jasminum* or Oleaceae species?**

Plastid genomes would be useful because conserved plastid genes and genome regions can be compared among species to study their evolutionary relationships.

### Research question where nuclear genomic data would be more appropriate

**Which nuclear genetic variants are associated with important traits such as drought tolerance, disease resistance, or flowering time in *Jasminum*?**

Nuclear genomic data would be more appropriate because complex traits can involve many genes distributed throughout the nuclear genome and may not be represented by plastid DNA.

# Additional Plastid vs Mitochondrial Genome Comparison

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| Cellular location | Found inside plastids, such as chloroplasts. | Found inside mitochondria. |
| Main biological functions | Mainly involved in photosynthesis, carbon fixation, and other plastid functions. | Mainly involved in cellular respiration and energy production. |
| Typical genome organization | Usually a circular genome in land plants with an LSC region, SSC region, and two IR regions. Jasminum nudiflorum has this four-region organization, although its IRs are unusually large. | More variable than plastid genomes. Plant mitochondrial DNA can occur in different physical forms and can contain repeated sequences and recombined structures. |
| Relative genome size | Usually relatively small and conserved in land plants, commonly around 150 kb. The J. nudiflorum chloroplast genome is 165,121 bp. | Usually more variable in plants and can be much larger than plastid genomes. |
| Gene content | Contains genes involved in photosynthesis, transcription, translation, RNA processing, and other plastid functions. | Contains genes mainly involved in mitochondrial respiration and related functions. |
| Copy number | Multiple copies of plastid DNA can occur within cells or chloroplasts. | Multiple copies of mitochondrial DNA can occur within cells or mitochondria. |
| Inheritance | Often inherited from one parent, commonly the maternal parent in many plants, but this varies among plant lineages. | Often inherited from one parent, commonly maternal in many plants, but exceptions occur. |
| Recombination / structural change | Can undergo inversions, duplications, insertions, gene loss, intron loss, IR expansion, and other rearrangements. J. nudiflorum is an example of a plastome with substantial structural rearrangement. | Plant mitochondrial genomes are often structurally dynamic and can undergo recombination between repeated sequences. |
| Common research applications | Plant identification, DNA barcoding, phylogenetic studies, evolutionary research, species comparisons, plant diversity, and plastid genome engineering. | Plant evolution, mitochondrial inheritance, genome rearrangements, respiration-related genes, cytoplasmic male sterility, and mitochondrial genome evolution. |

# References

Primary data source: NCBI Nucleotide / RefSeq. Jasminum nudiflorum chloroplast, complete genome. Accession NC_008407.1.

Associated publication: Lee, H.-L., Jansen, R. K., Chumley, T. W., & Kim, K.-J. (2007). Gene relocations within chloroplast genomes of Jasminum and Menodora (Oleaceae) are due to multiple, overlapping inversions. Molecular Biology and Evolution, 24(5), 1161–1180.

Galaxy: https://usegalaxy.org/u/doreenmariepuyat/h/plastid-jasminum-puyat

NCBI Nucleotide: https://www.ncbi.nlm.nih.gov/nuccore/?term=jasminum+chloroplast+complete+genome

GenBank: https://www.ncbi.nlm.nih.gov/nuccore/NC_008407.1

Galaxy Training Network: https://usegalaxy.org/?tool_id=toolshed.g2.bx.psu.edu%2Frepos%2Fiuc%2Ffasta_stats%2Ffasta-stats%2F2.0&version=latest

# Reproducibility Summary

1. Retrieve NC_008407.1 from NCBI Nucleotide/RefSeq.
2. Download the complete chloroplast genome in FASTA format.
3. Upload the FASTA file to a personal Galaxy history.
4. Use FASTA Statistics to obtain genome length, sequence count, GC content, N50, L50, and gap information.
5. Retain the annotated GenBank/RefSeq record for gene, intron, and structural-feature characterization.
6. Record the LSC, SSC, and IR organization from the associated complete-genome publication.
7. Summarize gene groups, RNA features, introns, duplications, and unusual structural features.
8. Save screenshots of the NCBI record, FASTA record, and Galaxy analysis as figures.
9. Store the FASTA, annotated record, results, figures, and this report in the GitHub repository so another student can repeat the analysis.
