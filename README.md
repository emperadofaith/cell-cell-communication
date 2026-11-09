## Title - Macrophage-Mediated Cell-to-Cell Communication: CCL2–CCR2 Signaling in Monocyte Recruitment

### Biological Question:

How does CCL2 released by activated macrophages interact with CCR2 receptors on monocytes to promote immune cell migration toward sites of inflammation?

## Chosen Sender Cell and Biological Context

**Chosen sender cell:** Macrophage

**Biological context:** Inflammation and immune response

Macrophages are immune cells found in various tissues that recognize pathogens, remove cellular debris, and regulate inflammation. During an inflammatory response, activated macrophages can release C-C motif chemokine ligand 2 (CCL2), also known as monocyte chemoattractant protein-1 (MCP-1). CCL2 binds to CCR2 receptors on monocytes, promoting their migration toward inflamed tissues and supporting the recruitment of immune cells to affected areas.

## Candidate Ligand and Evidence for Sender-Cell Expression

**Signaling molecule:** C-C motif chemokine ligand 2 (CCL2), also known as monocyte chemoattractant protein-1 (MCP-1).

**Official gene symbol:** CCL2

**Signaling type:** Paracrine signaling

Expression evidence: The Human Protein Atlas identifies CCL2 as a secreted protein with evidence at the protein level. Its single-cell RNA expression is enhanced in several cell types, including Hofbauer cells, which are specialized placental macrophages. This supports the biological plausibility of CCL2 production by macrophage-lineage cells.

Biological function: CCL2 is a chemokine that attracts monocytes toward sites of inflammation by binding to CCR2 receptors. This interaction promotes monocyte migration and contributes to immune cell recruitment during inflammatory responses.

## Receptor and Receiver Cell Expression Evidence

The Human Protein Atlas identifies CCR2 as a membrane-associated G-protein coupled receptor with evidence at the protein level. Its single-cell RNA expression is group enriched in several cell types, including monocytes and monocyte progenitors. CCR2 is also associated with the monocyte and neutrophil inflammatory signaling expression cluster. These findings support the selection of monocytes as receiver cells in the proposed CCL2–CCR2 signaling mechanism.

## Cell-to-Cell Communication

Activated macrophages release CCL2, a secreted chemokine that can bind to CCR2 receptors on monocytes. This interaction activates intracellular signaling pathways that promote monocyte chemotaxis and recruitment toward inflamed tissues. The proposed mechanism represents paracrine signaling during inflammation.

## STRING Protein-Association Network and Functional Enrichment

**Proteins analyzed:** CCL2, CCR2, GNAI2, GNB1, PIK3CG, AKT1, and MAPK1.

#### Network Statistics

- **Number of nodes:** 7
- **Number of edges:** 18
- **Expected edges:** 7
- **Average node degree:** 5.14
- **Average clustering coefficient:** 0.833
- **PPI enrichment p-value:** 0.000277

#### Relevance of Each Protein

- **CCL2:** A chemokine released by activated macrophages that attracts monocytes toward inflamed tissues.
- **CCR2:** A cell-surface receptor that recognizes CCL2 and initiates signaling involved in monocyte migration.
- **GNAI2:** A G-protein subunit that transmits signals from activated receptors to intracellular signaling pathways.
- **GNB1:** A G-protein beta subunit that participates in signal transmission and regulation of downstream effectors.
- **PIK3CG:** An enzyme involved in PI3K signaling that helps regulate cell movement and migration.
- **AKT1:** A protein kinase involved in downstream signaling that regulates cell survival and migration-related responses.
- **MAPK1:** A protein kinase involved in the MAPK/ERK pathway that regulates cellular responses, including changes associated with migration.

#### Network Interpretation

The STRING network identified 18 functional associations among seven proteins, exceeding the seven expected interactions (p = 0.000277). These proteins are associated with chemokine receptor signaling and downstream pathways involved in cell migration. The findings support the proposed CCL2–CCR2 signaling mechanism in monocyte recruitment during inflammation. STRING associations do not necessarily indicate direct physical interactions.

#### Functional Enrichment

The most relevant enriched pathway was the **KEGG Chemokine Signaling Pathway (hsa04062)**, involving all seven analyzed proteins (FDR = 2.55 × 10⁻¹²). Other significant findings included:

- **Chemokine signaling (WikiPathways):** FDR = 2.10 × 10⁻⁹
- **G beta:gamma signaling through PI3Kgamma (Reactome):** FDR = 3.12 × 10⁻⁵
- **Regulation of mononuclear cell migration (GO):** FDR = 0.00017
- **Positive regulation of cell migration (GO):** FDR = 1.43 × 10⁻⁵

#### Enrichment Interpretation

The enrichment results indicate that the analyzed proteins are significantly associated with chemokine signaling and cell migration. These findings are consistent with CCL2 binding to CCR2 on monocytes and activating intracellular pathways that promote chemotaxis and recruitment toward inflamed tissues.

## IntAct Molecular Interaction Validation

**Interacting molecules:** RELA protein and CCL2 gene    
**Detection method:** Chromatin immunoprecipitation (ChIP)  
**Interaction type:** Association  
**Experimental source:** Human peripheral blood mononuclear cells  
**Publication PMID:** 20952659  
**IntAct accession:** EBI-10049794  

#### Interaction Interpretation

The IntAct database identified an association between the RELA protein and the CCL2 gene using chromatin immunoprecipitation (ChIP) in human peripheral blood mononuclear cells. RELA is a component of the NF-κB transcription factor complex involved in regulating inflammatory gene expression. The result supports an association of RELA with the CCL2 genomic region, consistent with its possible role in CCL2 transcriptional regulation. However, ChIP does not establish direct protein-protein binding or confirm the CCL2–CCR2 ligand-receptor interaction.

#### Evidence and Limitations

The IntAct record provides experimental evidence for a regulatory association involving RELA and CCL2. However, the experiment was performed using peripheral blood mononuclear cells rather than isolated macrophages. Therefore, the result cannot independently confirm CCL2 regulation in macrophages or its binding to CCR2 on monocytes.

## Final Cell-to-Cell Communication Model

<img width="672" height="657" alt="image" src="https://github.com/user-attachments/assets/58734cc6-d6e7-4484-88ba-99a5810964ba" />

#### Model Interpretation

The proposed model illustrates paracrine communication between macrophages and monocytes during inflammation. Activated macrophages can release C-C motif chemokine ligand 2 (CCL2), which binds to CCR2 receptors on nearby monocytes and promotes their migration toward inflamed tissues.

The Human Protein Atlas identified CCL2 as a secreted protein with enhanced expression in Hofbauer cells, a specialized macrophage population. It also showed that CCR2 expression is enriched in cell groups that include monocytes, supporting the selection of these cells as signal receivers. OmniPath classified CCL2 as a secreted signaling molecule and CCR2 as a transmembrane receptor.

STRING identified 18 functional associations among seven analyzed proteins, with significant enrichment of the KEGG chemokine signaling pathway (FDR = 2.55 × 10⁻¹²). GNAI2, GNB1, PIK3CG, AKT1, and MAPK1 are associated with signaling pathways that can contribute to cellular migration.

IntAct provided ChIP evidence for an association between RELA and the CCL2 gene, supporting a possible regulatory relationship. This evidence does not directly establish CCL2–CCR2 binding or signaling in the selected cells.

Overall, the model is consistent with macrophage-mediated recruitment of monocytes during inflammation, although the exact signaling events in these cells require further experimental validation.

## Guide Questions

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

The chosen sender cell was the macrophage, an immune cell found in various tissues. Macrophages participate in innate immunity by recognizing pathogens, removing cellular debris, and releasing signaling molecules that regulate inflammation and recruit other immune cells.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

The identified signaling molecule was C-C motif chemokine ligand 2 (CCL2), a secreted chemokine involved in monocyte recruitment. The Human Protein Atlas identified CCL2 expression in Hofbauer cells, a specialized macrophage population, supporting its association with macrophages. OmniPath also classified CCL2 as a secreted protein.

### 3. What receptor receives the signal, and which receiver cell did you select?

The receptor was C-C chemokine receptor type 2 (CCR2), and the selected receiver cell was the monocyte. The Human Protein Atlas showed enriched CCR2 expression in cell groups including monocytes, while OmniPath classified CCR2 as a transmembrane receptor. CCR2 recognizes CCL2 and mediates signaling associated with monocyte migration.

### 4. What type of cell-to-cell signaling is represented: paracrine, endocrine, autocrine, or contact-dependent?

The proposed mechanism represents paracrine signaling because macrophages release CCL2 into the extracellular environment, where it can activate CCR2 receptors on nearby monocytes. This communication promotes monocyte recruitment toward inflamed tissues.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.

The most relevant proteins were CCR2, GNAI2, GNB1, PIK3CG, and AKT1. CCR2 receives the CCL2 signal, while GNAI2 and GNB1 participate in G-protein signaling. PIK3CG and AKT1 contribute to downstream signaling pathways associated with cell migration. These proteins provide a proposed connection between receptor activation and monocyte chemotaxis.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

The KEGG Chemokine Signaling Pathway (hsa04062) was significantly enriched, involving all seven analyzed proteins (FDR = 2.55 × 10⁻¹²). The network was also enriched for regulation of mononuclear cell migration (FDR = 0.00017). These findings are consistent with CCL2–CCR2 signaling and monocyte recruitment during inflammation.

### 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

IntAct identified an association between the RELA protein and the CCL2 gene in human peripheral blood mononuclear cells. The interaction was investigated using chromatin immunoprecipitation (ChIP), with publication PMID 20952659 and IntAct accession EBI-10049794. The evidence supports an association involving RELA and the CCL2 genomic region but does not establish direct CCL2–CCR2 protein binding.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

The secreted nature of CCL2, the receptor function of CCR2, and CCR2 expression in monocytes are supported by database annotations. STRING also supports functional associations among proteins involved in chemokine signaling and cell migration. However, the exact sequence of intracellular signaling events and their activity in the selected macrophage–monocyte system remain inferred because the analyses did not directly measure signaling or cell migration.

### 9. What cellular response is expected in the receiver cell, and why?

The expected response is monocyte chemotaxis, or directed migration toward inflamed tissues. CCL2 binding to CCR2 activates intracellular signaling pathways that regulate cell movement, allowing monocytes to migrate along a chemokine gradient and participate in the inflammatory response.

## References and Database Links

### Databases Used

1. **Human Protein Atlas.** (2026). CCL2: C-C motif chemokine ligand 2.  
   https://www.proteinatlas.org/ENSG00000108691-CCL2

2. **Human Protein Atlas.** (2026). CCR2: C-C motif chemokine receptor 2.  
   https://www.proteinatlas.org/ENSG00000121807-CCR2

3. **OmniPath Explorer.** (2026). Intercellular signaling annotations for CCL2 and CCR2.  
   https://explore.omnipathdb.org/

4. **STRING Database.** (2026). Protein-association network and functional enrichment analysis of CCL2, CCR2, GNAI2, GNB1, PIK3CG, AKT1, and MAPK1 in *Homo sapiens*.  
   https://string-db.org/

5. **IntAct Molecular Interaction Database.** (2026). RELA–CCL2 gene association, IntAct accession EBI-10049794, PMID: 20952659.  
   https://www.ebi.ac.uk/intact/

### Supporting Scientific Publications

6. Szklarczyk, D., et al. (2025). The STRING database in 2025: Protein networks with directionality of regulation. *Nucleic Acids Research, 53*(D1), D730–D737.  
   https://doi.org/10.1093/nar/gkae1113

7. Orchard, S., et al. (2014). The MIntAct project—IntAct as a common curation platform for 11 molecular interaction databases. *Nucleic Acids Research, 42*(D1), D358–D363.  
   https://doi.org/10.1093/nar/gkt1115










