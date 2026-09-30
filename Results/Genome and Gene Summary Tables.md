## Data Source and Genome Selection
| Item                       | Information                                                                                                                                      |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Chosen genus**           | *Jasminum*                                                                                                                                       |
| **Selected species**       | *Jasminum nudiflorum*                                                                                                                            |
| **Common name**            | Winter jasmine                                                                                                                                   |
| **Family**                 | Oleaceae                                                                                                                                         |
| **Organelle**              | Chloroplast (plastid)                                                                                                                            |
| **Genome type**            | Complete chloroplast genome                                                                                                                      |
| **NCBI accession/version** | **NC_008407.1**                                                                                                                                  |
| **Database**               | NCBI RefSeq / Nucleotide                                                                                                                         |
| **Genome length**          | **165,121 bp**                                                                                                                                   |
| **Topology**               | Circular                                                                                                                                         |
| **Sequence status**        | Complete genome                                                                                                                                  |
| **Source**                 | NCBI Nucleotide / RefSeq                                                                                                                         |
| **Associated publication** | Lee et al. (2007), *Gene relocations within chloroplast genomes of Jasminum and Menodora (Oleaceae) are due to multiple, overlapping inversions* |
| **NCBI record**            | [NCBI Nucleotide record — NC_008407.1](https://www.ncbi.nlm.nih.gov/nuccore/NC_008407.1?utm_source=chatgpt.com)                                  |

## Files to Obtain
| File                   | Format                  | Purpose                                                                | File/Accession                                            |
| ---------------------- | ----------------------- | ---------------------------------------------------------------------- | --------------------------------------------------------- |
| **Genome sequence**    | FASTA                   | Upload to Galaxy and obtain sequence statistics                        | *Jasminum nudiflorum* chloroplast genome, **NC_008407.1** |
| **Annotated genome**   | GenBank / RefSeq        | Identify genes, coordinates, introns, duplications, and other features | *Jasminum nudiflorum* chloroplast genome, **NC_008407.1** |
| **Source information** | NCBI record / accession | Document the origin of the genome used                                 | **NC_008407.1** — NCBI Nucleotide                         |

## Galaxy Workflow
| Statistic                                         |  Galaxy Result |
| ------------------------------------------------- | -------------: |
| **Genome length**                                 | **165,121 bp** |
| **Number of sequence records**                    |          **1** |
| **GC content**                                    |     **37.98%** |
| **Gaps**                                          |          **0** |
| **Complete plastome represented by one sequence** |        **Yes** |
| **N50**                                           | **165,121 bp** |
| **L50**                                           |          **1** |
Interpretation: The FASTA contains a single continuous sequence of 165,121 bp, matching the NCBI genome length. 
The absence of gaps and the single sequence record are consistent with a complete plastome.

## Required Plastid Genome Characterization
| Characteristic                    | *Jasminum nudiflorum* chloroplast genome                                                          |
| --------------------------------- | ------------------------------------------------------------------------------------------------- |
| **Genus**                         | *Jasminum*                                                                                        |
| **Species**                       | *Jasminum nudiflorum*                                                                             |
| **Family**                        | Oleaceae                                                                                          |
| **NCBI accession/version**        | **NC_008407.1**                                                                                   |
| **Genome size**                   | **165,121 bp**                                                                                    |
| **GC content**                    | **37.98%**                                                                                        |
| **Topology**                      | Circular                                                                                          |
| **LSC size**                      | **121,851 bp***                                                                                   |
| **SSC size**                      | **13,538 bp***                                                                                    |
| **IR size**                       | **14,866 bp each***                                                                               |
| **Number of sequence records**    | **1**                                                                                             |
| **Total annotated gene features** | **131**                                                                                           |
| **Protein-coding genes (CDS)**    | **85**                                                                                            |
| **tRNA genes**                    | **38**                                                                                            |
| **rRNA genes**                    | **8**                                                                                             |
| **Introns**                       | **23 annotated intron features**                                                                  |
| **Pseudogenes**                   | **No pseudogene feature identified in the current GenBank annotation**                            |
| **Gene duplications**             | Several genes occur in two copies, particularly genes associated with the inverted-repeat regions |
| **Overall organization**          | **LSC–IR–SSC–IR**                                                                                 |

## Gene Groups Identified
| Gene group | Examples / what to look for                  | Main function                                                                               |
| ---------- | -------------------------------------------- | ------------------------------------------------------------------------------------------- |
| **psa**    | *psa* genes such as *psaA*                   | Involved in Photosystem I and photosynthesis.                                               |
| **psb**    | *psb* genes such as *psbA*                   | Involved in Photosystem II and photosynthesis.                                              |
| **atp**    | *atp* genes such as *atpA*                   | Encode components of ATP synthase involved in ATP production.                               |
| **pet**    | *pet* genes such as *petB*, *petD*           | Encode components of the cytochrome b6f complex involved in electron transport.             |
| **rbcL**   | *rbcL*                                       | Encodes the large subunit of RuBisCO involved in carbon fixation.                           |
| **rpo**    | *rpo* genes such as *rpoA* and *rpoC1*       | Encode RNA polymerase components used in transcription.                                     |
| **rpl**    | *rpl* genes such as *rpl2*, *rpl16*, *rpl23* | Encode ribosomal proteins of the large ribosomal subunit.                                   |
| **rps**    | *rps* genes such as *rps7*, *rps12*, *rps16* | Encode ribosomal proteins of the small ribosomal subunit.                                   |
| **rrn**    | *rrn16*, *rrn23*, *rrn4.5*, *rrn5*           | Encode ribosomal RNA.                                                                       |
| **trn**    | *trn* / tRNA genes                           | Encode transfer RNAs used during protein synthesis.                                         |
| **matK**   | *matK*                                       | Encodes maturase K, involved in RNA processing/splicing.                                    |
| **clpP**   | *clpP*                                       | Encodes a protease component involved in protein processing/degradation
