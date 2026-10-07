## Cell-Cell-Communication

### Proposed TGFB1–TGFBR2 Signaling Between Trophoblasts and Placental Endothelial Cells

### Biological Question

Can TGFB1 from trophoblasts signal to TGFBR2 on placental endothelial cells and regulate cellular activities involved in placental development?

## Chosen sender cell and biological context

| **Item**               | **Answer**                                                                                                  |
| ---------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Sender cell**        | Trophoblast                                                                                                 |
| **Biological context** | Placental development and cell-to-cell communication                                                        |
| **Main purpose**       | May help regulate cell growth, development, and other cellular activities involved in placental development |

## Candidate ligand and evidence for sender-cell expression

| Item | Information |
|---|---|
| Sender cell | Trophoblast |
| Candidate gene | TGFB1 |
| Protein name | Transforming growth factor beta 1 |
| Expression evidence | Low protein expression in trophoblastic cells |
| Source | https://www.proteinatlas.org/ENSG00000105329-TGFB1 |

## Receptor and receiver cell with supporting evidence

| **Item**                   | **Information** |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Ligand                     | TGFB1 (Transforming growth factor beta 1), encoded by *TGFB1* |
| Receptor                   | TGFBR2 (Transforming growth factor beta receptor 2), encoded by *TGFBR2* |
| Receiver cell              | Placental endothelial cell |
| Signaling context          | TGF-beta signaling; TGFB1–TGFBR2 signaling can activate downstream SMAD proteins and regulate gene expression involved in cell growth, differentiation, and development. |
| Supporting source Omnipath | https://explore.omnipathdb.org/search?q=TGFB1%2C+&tab=intercell&species=9606&parents=ligand , https://explore.omnipathdb.org/search?q=TGFBR2a2C&tab=intercell&species=9606&parents=receptor|
| Supporting source HPA | https://www.proteinatlas.org/ENSG00000105329-TGFB1 |

## OmniPath evidence

| **Component** | **Gene** | **Role**                   |
| ------------- | -------- | -------------------------- |
| TGFB1         | `TGFB1`  | Ligand/signal              |
| TGFBR2        | `TGFBR2` | Receptor on receiver cells |

## STRING network image and interpretation

| **STRING Result**                |    **Value** |
| -------------------------------- | -----------: |
| **Number of proteins**           |           11 |
| **Observed edges**               |           53 |
| **Expected edges**               |           15 |
| **PPI enrichment p-value**       | 1.14 × 10⁻¹⁴ |
| **Average node degree**          |         9.64 |
| **Local clustering coefficient** |        0.968 |

**Interpretation**

### STRING Network Image and Interpretation

<img width="572" height="433" alt="Screenshot 2026-10-07 091425" src="https://github.com/user-attachments/assets/c8146917-e0a0-41b7-a974-a75069ca9ce5" />

The STRING network contains 11 proteins and 53 connections, which is much higher than the 15 expected connections (PPI enrichment p-value = 1.14 × 10⁻¹⁴). This suggests that the proteins in the network are strongly related to each other. The enriched biological processes include regulation of SMAD protein signal transduction and the TGF-beta receptor signaling pathway. The molecular functions are also related to TGF-beta receptor binding and SMAD binding. Overall, the results support that TGFBR2, TGFBR1, SMAD2, SMAD3, and SMAD4 are connected to the TGF-beta/SMAD signaling pathway, supporting the proposed TGFB1–TGFBR2 signaling model.

| **Item**             | **Information**                                                                                                        |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **Enriched process** | Regulation of SMAD protein signal transduction, positive regulation of SMAD signaling, and TGF-beta receptor signaling |
| **STRING evidence**  | 11 proteins; 53 observed edges; PPI enrichment p-value = 1.14 × 10⁻¹⁴                                                  |
| **Protein 1**        | TGFBR2 – receptor for TGFB1 that helps initiate TGF-beta signaling                                                     |
| **Protein 2**        | TGFBR1 – receptor that works with TGFBR2 to transmit the TGF-beta signal                                               |
| **Protein 3**        | SMAD2 – signaling protein involved in transmitting TGF-beta signals inside the cell                                    |
| **Protein 4**        | SMAD3 – signaling protein that works with SMAD2 in TGF-beta signaling                                                  |
| **Protein 5**        | SMAD4 – signaling protein that helps regulate gene expression after TGF-beta signaling                                 |

## IntAct validation

| **Item**                          | **Information**                                                                                           |
| --------------------------------- | --------------------------------------------------------------------------------------------------------- |
| **Protein pair**                  | TGFB1 – TGFBR2                                                                                            |
| **IntAct record**                 | EBI-3504782                                                                                               |
| **Interaction type**              | Direct interaction                                                                                        |
| **Experimental detection method** | Crosslinking                                                                                              |
| **Organism**                      | Homo sapiens (human)                                                                                      |
| **Host organism**                 | Homo sapiens EW-7 Ewing's sarcoma cell                                                                    |
| **Positive interaction**          | Yes                                                                                                       |
| **Publication**                   | Pardali et al. (2011), "Critical role of endoglin in tumor cell plasticity of Ewing sarcoma and melanoma" |
| **Journal**                       | Oncogene                                                                                                  |
| **Publication reference**         | PMID: 20856203 ; https://doi.org/10.1038/onc.2010.418                                                     |
| **Evidence conclusion**           | Supports a direct physical interaction between TGFB1 and TGFBR2 in the experimental context.              |

I chose TGFB1 (TGF-β1) and TGFBR2 because they are the ligand and receptor in the proposed TGF-beta signaling pathway. IntAct contains a curated interaction record for this protein pair. The interaction was detected through a crosslinking experiment using human EW-7 Ewing's sarcoma cells. IntAct reports the interaction as direct and positive, providing experimental evidence that TGFB1 can physically interact with TGFBR2. This finding supports the proposed TGFB1 → TGFBR2 signaling pathway. Since IntAct already provides experimental evidence for this protein pair, examining another pair is not necessary.

## Final model and 150–250 word interpretation

<img width="860" height="696" alt="Screenshot 2026-10-07 103133" src="https://github.com/user-attachments/assets/cb112f65-d525-4a0d-b141-537a1da2783f" />

This model proposes that trophoblasts may communicate with placental endothelial cells through TGFB1–TGFBR2 signaling. TGFB1 serves as the proposed ligand, while TGFBR2 works together with TGFBR1 to transmit the signal inside the receiving cell. The STRING results connect TGFBR1, SMAD2, SMAD3, SMAD4, and SMAD7 with the TGF-beta signaling pathway. SMAD2 and SMAD3 can interact with SMAD4 and help regulate gene activity in the nucleus, which may influence cell growth, development, and placental development.

Each database provides different evidence for the proposed model. OmniPath provides information about the ligand and receptor, while the Human Protein Atlas gives expression information for TGFB1 and TGFBR2. STRING shows relationships among proteins involved in TGF-beta signaling, and IntAct provides experimental evidence of an interaction between TGFB1 and TGFBR2. However, these findings do not confirm that the complete pathway occurs specifically between trophoblasts and placental endothelial cells. Evidence for TGFB1 production by trophoblasts is also limited. Therefore, further experiments would be needed to confirm this proposed cell-to-cell signaling pathway.

## Questions and Answers

**1. What sender cell did you choose, and in what tissue or biological context does it act?**

I chose trophoblasts as the sender cells. They are found in the placenta and are involved in placental development and communication with other cells.

**2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?**

The signaling molecule I identified is TGFB1. The Human Protein Atlas shows TGFB1 expression in placental tissue, but there is limited evidence that specifically shows that trophoblasts produce it.

**3. What receptor receives the signal, and which receiver cell did you select?**

The receptor is TGFBR2, and I selected placental endothelial cells as the receiver cells.

**4. What type of cell-to-cell signaling is represented?**

The proposed signaling is paracrine signaling because the signal is expected to act on a different nearby cell.

**5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.**

The most relevant proteins are TGFBR1, SMAD2, SMAD3, SMAD4, and SMAD7. They are connected to the TGF-beta signaling pathway and help pass or regulate the signal inside the cell.

**6. What enriched pathway or biological process is consistent with your proposed mechanism?**

The enriched pathways include the TGF-beta receptor signaling pathway and regulation of SMAD protein signal transduction. These results support the proposed TGFB1–TGFBR2 signaling pathway.

**7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?**

IntAct showed a direct interaction between TGFB1 and TGFBR2. The interaction was supported by a crosslinking experiment using human EW-7 Ewing's sarcoma cells.

**8. Which parts of your final model are strongly supported, and which parts remain an inference?**

The TGFB1–TGFBR2 interaction and the involvement of the TGF-beta/SMAD pathway are supported by database evidence. However, the idea that trophoblasts release TGFB1 to signal to placental endothelial cells is still an inference because the evidence for trophoblast-specific TGFB1 production is limited.

**9. What cellular response is expected in the receiver cell, and why?**

The expected response is changes in gene expression that may affect cell growth and development. This is because the TGF-beta pathway can send signals to the nucleus through SMAD proteins.

## References and database links

HPA : https://www.proteinatlas.org/ENSG00000105329-TGFB1

OmniPath : https://explore.omnipathdb.org/search?q=TGFB1%2C+&tab=intercell&species=9606&parents=ligand

           https://explore.omnipathdb.org/search?q=TGFBR2a2C&tab=intercell&species=9606&parents=receptor

STRING : https://string-db.org/cgi/network?taskId=bl72mlM0wFTY&sessionId=biwhV190xIlA

IntAct : https://www.ebi.ac.uk/intact/details/interaction/EBI-3504782
