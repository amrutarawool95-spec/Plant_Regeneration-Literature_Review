# Literature Review: Plant Regeneration â€” Cellular Origins and Molecular Mechanisms

**Source:** Ikeuchi, M., Ogawa, Y., Iwase, A. & Sugimoto, K. (2016). *Plant regeneration: cellular origins and molecular mechanisms.* Development 143, 1442â€“1451. doi:10.1242/dev.134668

**Reviewer:** Amruta Rawool
**Type:** Review article (RIKEN Center for Sustainable Resource Science)

---

## 1. Overview

This review synthesizes what is known about how plants regenerate lost or damaged tissue, spanning single-celled algae to complex seed plants, and connects classical tissue-culture observations to the modern transcription-factor networks that control the process. The central theme is that plant regeneration always relies on **cellular plasticity** â€” the ability of a cell to change or re-acquire developmental fate â€” achieved through two broad routes: reactivating existing but relatively undifferentiated cells, or reprogramming fully differentiated somatic cells.

The authors organize the review around four questions:
1. How diverse is regeneration across the plant kingdom?
2. Which cells serve as the starting material for regeneration?
3. What molecular/genetic circuits control the major regeneration pathways (de novo shoot organogenesis, de novo root organogenesis, somatic embryogenesis)?
4. What developmental, epigenetic, and environmental factors constrain regenerative capacity?

---

## 2. Evolutionary Diversity of Regeneration

| Lineage | Mode of regeneration | Key example |
|---|---|---|
| Unicellular green algae | Whole-body regeneration from a single cell via de novo protoplast formation | *Bryopsis plumosa*: nuclei extruded from a wound aggregate in seawater and rebuild the cell membrane from scratch |
| Liverworts | New apical meristem formation at wound sites | *Marchantia polymorpha* forms new meristems within ~60 h of wounding, mainly from the ventral midrib |
| Mosses | Fate conversion of leaf cells into stem cells | *Physcomitrella patens* leaf cells adjacent to a cut convert into protonema stem cells within 48 h |
| Seed plants | Highly diverse: meristem repair, axillary outgrowth, lateral root formation, de novo organogenesis, somatic embryogenesis | Many ornamental and crop species (see below) |

A key point: complexity of body plan correlates with diversity of regeneration strategies. Simple bryophytes largely rely on direct fate conversion of existing cells, while seed plants have evolved multiple parallel repair and *de novo* organ-formation strategies.

### Seed-plant strategies (six categories described)
- **Meristem reconstruction** â€” surrounding cells rebuild an ablated shoot or root apical meristem.
- **Tissue repair** â€” vascular/tissue healing after partial wounding (e.g., after debarking or grafting).
- **Axillary shoot outgrowth** â€” loss of apical dominance releases dormant axillary buds.
- **Lateral root formation** â€” pericycle-derived new root meristems after root meristem loss.
- **De novo organogenesis** â€” entirely new shoots and/or roots form from cut explants (leaves, stems, petioles, bulb scales), seen across many ornamental and crop families (Crassulaceae, Gesneriaceae, etc.).
- **Somatic embryogenesis (in vitro)** â€” protoplasts, pollen, or callus cells form embryo-like structures resembling zygotic embryos.

---

## 3. Cellular Origins of Regeneration

Two overarching strategies are proposed:

1. **Reactivation of relatively undifferentiated cells** â€” e.g., pericycle cells (a long-standing stem-cell-competent tissue in roots), which are the primary source of both lateral roots and much of *in vitro* shoot/root regeneration and somatic embryogenesis.
2. **Reprogramming of fully differentiated somatic cells** â€” e.g., mature leaf epidermal cells in *Chirita flavimaculata*, stem cortex cells in *Chrysanthemum morifolium*, and Arabidopsis leaf epidermal cells reprogrammed into embryos purely by overexpressing the transcription factor **RKD4**.

This leads to an important conceptual conclusion: developmental "youth" is *not* a prerequisite for regeneration â€” under the right hormonal/genetic conditions, fully mature, differentiated cells can still be redirected into a pluripotent or embryonic state.

---

## 4. Wounding as the Universal Trigger

Across nearly all natural regeneration events, tissue damage (wounding) is the shared inductive cue. In Arabidopsis, intact, un-wounded tissue regenerates shoots very poorly even on the correct hormone media, showing that wound signaling itself is required, not just hormone exposure.

**Key regulator: WIND1â€“4 (AP2/ERF transcription factors)**
- Rapidly induced by wounding.
- Promote callus formation and dedifferentiation at cut sites.
- WIND1 overexpression alone is sufficient to trigger shoot/root regeneration even without wounding; a dominant-negative WIND1 impairs regeneration.
- Implicated in activating cytokinin signaling downstream of the wound signal.
- Sequential WIND1 â†’ LEC2 (an embryonic master regulator) activation can trigger somatic embryogenesis even at non-wounded sites, while LEC2 alone only works at cut sites â€” illustrating how wound signaling and cell-fate reprogramming genes interact.

---

## 5. Molecular Pathways for the Three Major Regeneration Programs

### 5.1 De novo shoot organogenesis (callus-inducing medium â†’ shoot-inducing medium)
- Callus induced on auxin-rich **CIM** resembles a lateral-root-meristem-like tissue.
- **PLT3/PLT5/PLT7** (PLETHORA family, AP2/ERF) are induced early on CIM â†’ activate **PLT1/PLT2** (root meristem identity) and **CUC1/CUC2** (shoot meristem initiation, NAC family).
- On transfer to cytokinin-rich **SIM**: **WUSCHEL (WUS)** is induced in high-cytokinin domains, while **CUC2** stays restricted to low-cytokinin domains â€” this auxin/cytokinin partitioning defines shoot meristem identity.
- **PIN1** and **STM** refine spatial patterning of the new meristem (promeristem).
- Additional AP2/ERF factors **ESR1/DRN** and **ESR2/DRNL** reinforce shoot fate, partly by boosting CUC1 expression.

### 5.2 De novo root organogenesis
- On CIM + root-inducing medium (RIM), pericycle cells regenerate roots.
- In detached-leaf regeneration: auxin accumulation at cut sites induces **WOX11** and **WOX12** in procambium/parenchyma cells, converting them into "root founder cells."
- WOX11/12 â†’ activate **LBD16**, **LBD29**, then **WOX5** to establish the new root meristem.
- The same WOX11/LBD/WOX5 module is shared with normal lateral root formation from pericycle cells, suggesting a conserved auxin-driven root-meristem-initiation circuit.
- WOX11 induction requires auxin-response elements in its own promoter â€” direct evidence that ARF-family auxin response factors activate this pathway.

### 5.3 Somatic embryogenesis
- Inducible by diverse abiotic stresses (salt, heavy metals, osmotic stress, heat) as well as auxin (notably 2,4-D), which appears to trigger both stress and auxin signaling simultaneously.
- An auxin gradient forms in embryonic callus; **WUS** expression becomes restricted to *low*-auxin domains (opposite pattern from shoot regeneration), marking future shoot meristem position.
- WUS induces **LEC1**, **LEC2**, and **FUS3** (classic zygotic-embryogenesis regulators), which act with **AGL15** to:
 - Modulate auxin biosynthesis (via YUC genes) and signaling (via IAA30).
 - Shift the GA:ABA balance toward low GA (via GA2ox6/GA3ox1/GA3ox2 regulation) to favor an embryonic rather than vegetative developmental program.

---

## 6. Epigenetic Regulation â€” Keeping Regeneration in Check

Because differentiated cells retain latent regenerative capacity, plants must actively **repress** it during normal growth:

- **PRC2 (Polycomb Repressive Complex 2)** deposits H3K27me3 to silence reprogramming genes. PRC2-mutant Arabidopsis roots eventually reprogram spontaneously into callus/embryo-like structures. Direct PRC2 targets include **WIND3** and **LEC2**.
- Many core regeneration regulators (**WOX11, WOX5, WUS, STM**) are themselves under PRC2-mediated repression, suggesting Polycomb silencing is a general safeguard across pathways.
- **Histone deacetylation** (via HDA19/HDA6) also suppresses ectopic embryogenesis; loss-of-function mutants or the HDAC inhibitor trichostatin A (TSA) cause ectopic embryo-like structures via de-repression of LEC1/LEC2.
- **DNA methylation**: *MET1* mutants show enhanced shoot regeneration, associated with elevated WUS expression â€” indicating that DNA methylation, alongside histone marks, keeps regeneration-competence genes silenced under normal conditions.

**Takeaway:** Regeneration potential is a constitutively "repressed but present" cellular property, unlocked when the relevant chromatin marks are removed or bypassed (by wounding, stress, or engineered overexpression).

---

## 7. Natural (Genetic) Variation in Regeneration Capacity

Several QTL studies show regeneration efficiency is a heritable, tunable trait:

- **RPK1** (a leucine-rich-repeat receptor kinase) â€” major QTL for shoot regeneration across Arabidopsis accessions; implicated in ABA signaling.
- **Ferredoxin-nitrite reductase** â€” QTL distinguishing high- (Kasalath, indica rice) vs low- (Koshihikari, japonica rice) regeneration cultivars; introducing the high-activity allele improved regeneration in the low-performing cultivar.
- ***Rg1* locus** in wild tomato (*Solanum peruvianum*) boosts both root and shoot regeneration without altering auxin sensitivity or CUC expression; interacts genetically with **DELLA/GA signaling** (the *procera* mutant).

This section is directly relevant to **crop improvement**: identifying and introgressing high-regeneration alleles can make transformation and tissue-culture-based breeding more efficient in recalcitrant crop varieties.

---

## 8. Developmental and Environmental Constraints

**Aging / developmental stage**
- Regeneration capacity generally declines with plant age (well documented in woody species and Arabidopsis).
- Mechanism: age-dependent decline in **miR156** raises its target **SPL9**, which represses cytokinin-responsive **ARR (type-B)** transcription factors â€” reducing cytokinin responsiveness and shoot regeneration capacity in older tissue.
- The vegetative-to-reproductive transition is separately linked to reduced auxin responsiveness and lower root-regeneration capacity.

**Light**
- Effects are highly context-dependent â€” light can either promote or inhibit regeneration depending on species and stage.
- In Arabidopsis cotyledon culture, light exposure in the first few hours after excision is inhibitory; brief darkness (2â€“6 h) post-wounding improves shoot regeneration.
- **CRY1** (blue/UV-A receptor) inhibits shoot regeneration; **PHYA** (far-red receptor) protects against this inhibition; **HY5** downstream may protect tissue via anthocyanin accumulation.

---

## 9. Applied Significance

The review closes by linking mechanistic insight to biotechnology:
- Ectopic expression of **WUS** and **WIND1** has already been used to boost organ regeneration/somatic embryogenesis in multiple crops, improving transformation efficiency in otherwise recalcitrant species.
- Expression profiling of core regeneration regulators is being used to pre-screen crop cultivars for high regeneration capacity before starting transformation pipelines.
- Understanding epigenetic repression mechanisms (PRC2, HDACs, DNA methylation) opens a route to chemically or genetically "unlock" regeneration competence in hard-to-transform genotypes.

---

## 10. Critical Assessment / Notes for Further Reading

**Strengths**
- Excellent synthesis bridging classical hormone physiology (Skoog & Miller 1957 auxin:cytokinin ratio) with modern transcription-factor and epigenetic networks.
- Cross-species framing (algae â†’ bryophytes â†’ seed plants) highlights conserved vs. lineage-specific strategies.
- Clear figures mapping gene regulatory networks for each of the three major regeneration programs (shoot organogenesis, root organogenesis, somatic embryogenesis) â€” useful as a reference schematic.

**Open questions flagged by the authors**
- The precise cell types that initiate *natural* (non-tissue-culture) regeneration are still not well defined.
- Downstream targets of WIND transcription factors remain largely unknown.
- How epigenetic repression (PRC2, HDACs, methylation) is *relieved* during genuine wound response in planta is unresolved.
- Most detailed mechanistic knowledge comes from Arabidopsis tissue culture; non-model/crop species likely have distinct or only partially conserved circuits â€” an open area for genome-editing and NGS-based studies.

**Possible relevance to bioinformatics/computational follow-up**
- The gene regulatory networks summarized here (WINDâ€“PLTâ€“CUCâ€“WUS for shoots; WOX11/12â€“LBDâ€“WOX5 for roots; WUSâ€“LEC1/2â€“FUS3â€“AGL15 for embryos) are good candidates for comparative genomics or variant-effect analyses across species with differing regeneration capacity (e.g., comparing high- vs low-regenerating cultivars/accessions), and could pair well with QTL-adjacent variant annotation pipelines.

---

## 11. Full Reference List (as cited in review)

See `references.md` for the complete bibliography extracted from the paper, organized alphabetically as in the original.
