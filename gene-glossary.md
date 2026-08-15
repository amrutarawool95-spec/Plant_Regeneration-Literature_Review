# Quick-Reference Glossary â€” Genes, Pathways & Terms
### Companion to `literature-review.md` (Ikeuchi et al. 2016, *Development* 143:1442â€“1451)

## Core Concepts

| Term | Meaning |
|---|---|
| **Totipotency** | Capacity of a single cell to regenerate an entire organism (demonstrated classically in single carrot phloem cells). |
| **Pluripotency** | Capacity of a cell to give rise to multiple, but not necessarily all, cell/organ types. |
| **Cellular plasticity** | The broad ability of a cell to change or re-specify its developmental fate â€” the underlying phenomenon behind all forms of regeneration. |
| **De novo organogenesis** | Formation of entirely new organs (shoots and/or roots) from a wound or explant, without passing through an embryo-like stage. |
| **Somatic embryogenesis** | A somatic (non-gametic) cell forms an embryo-like structure resembling a zygotic embryo, which then develops into a whole plant. |
| **Callus** | An unorganized, proliferating mass of dedifferentiated/pluripotent cells formed at a wound or on hormone-rich culture medium. |
| **CIM / SIM / RIM** | Callus-Inducing Medium / Shoot-Inducing Medium / Root-Inducing Medium â€” standard tissue-culture hormone regimes (high auxin, then switched to high cytokinin for shoots or auxin-only for roots). |

## Hormones

| Hormone | Role in regeneration |
|---|---|
| **Auxin** | High auxin:cytokinin ratio favors root regeneration; drives callus formation, WOX11/12 induction, and establishes polarity gradients in embryogenic callus. |
| **Cytokinin** | High cytokinin:auxin ratio favors shoot regeneration; activates WUS expression in shoot-inducing conditions. |
| **Gibberellin (GA) / Abscisic acid (ABA)** | Low GA relative to ABA favors somatic embryogenesis; DELLA (GA-signaling repressor) mutants show reduced regeneration. |

## Key Genes / Transcription Factors by Pathway

**Wound response (upstream of all pathways)**
- `WIND1â€“WIND4` (AP2/ERF family) â€” wound-induced; drive dedifferentiation/callus formation; WIND1 sufficient to trigger regeneration without wounding.

**Shoot organogenesis**
- `PLT3, PLT5, PLT7` â€” PLETHORA AP2/ERF factors, earliest CIM response.
- `PLT1, PLT2` â€” establish pluripotent, root-meristem-like callus.
- `CUC1, CUC2` â€” NAC-family, shoot meristem initiation; CUC2 restricted to low-cytokinin domains.
- `WUS` (WUSCHEL) â€” shoot meristem stem-cell identity; induced in high-cytokinin domains.
- `ESR1/DRN`, `ESR2/DRNL` â€” reinforce shoot fate, enhance CUC1 expression.
- `PIN1`, `STM` â€” pattern the newly forming shoot meristem/promeristem.

**Root organogenesis**
- `WOX11, WOX12` â€” auxin-induced; convert leaf procambium/parenchyma cells into root founder cells.
- `LBD16, LBD29` â€” LATERAL ORGAN BOUNDARIES DOMAIN factors downstream of WOX11/12.
- `WOX5` â€” establishes new root meristem; shared with lateral root development from pericycle cells.

**Somatic embryogenesis**
- `WUS` â€” restricted to low-auxin domains in embryonic callus; marks future shoot meristem.
- `LEC1, LEC2, FUS3` â€” classic zygotic-embryo regulators, reactivated in somatic cells.
- `AGL15` â€” MADS-box factor; works with LEC2/FUS3 to modulate auxin/GA/ABA balance.
- `YUC2, YUC4, YUC10` â€” auxin biosynthesis genes induced by LEC1/LEC2.
- `IAA30` â€” negative regulator of auxin signaling, induced by LEC2/AGL15.
- `GA2ox6, GA3ox1, GA3ox2` â€” GA metabolism genes tuned by AGL15/FUS3 to lower GA levels.
- `RKD4` â€” RWP-RK protein; overexpression alone reprograms mature Arabidopsis leaf epidermal cells into embryos.

## Epigenetic Regulators (repress regeneration by default)

| Regulator | Mechanism | Effect when lost |
|---|---|---|
| **PRC2** (Polycomb Repressive Complex 2) | Deposits H3K27me3 on regeneration genes (incl. WIND3, LEC2, WOX11, WOX5, WUS, STM) | Spontaneous reprogramming into callus/embryo-like tissue |
| **HDA19 / HDA6** (histone deacetylases) | Suppress ectopic embryonic gene expression | Ectopic embryo-like structures form in shoots |
| **MET1** (DNA methyltransferase) | Maintains silencing of WUS and other targets | Enhanced shoot regeneration on SIM |

## Natural Variation / QTLs

| Locus | Species | Effect |
|---|---|---|
| `RPK1` | Arabidopsis (accessions) | Major QTL for shoot regeneration; linked to ABA signaling |
| Ferredoxin-nitrite reductase | Rice (japonica vs indica) | QTL explaining Koshihikari (low) vs Kasalath (high) regeneration difference |
| `Rg1` | Tomato (*Solanum peruvianum*) | Boosts root & shoot regeneration; interacts with DELLA/GA pathway (*procera* mutant) |

## Environmental / Developmental Modifiers

- **miR156 â†’ SPL9 â†’ ARR(B-type)** axis: declining miR156 with age raises SPL9, which represses cytokinin response and lowers shoot regeneration capacity in older tissue.
- **CRY1** (blue/UV-A photoreceptor): inhibits shoot regeneration under light.
- **PHYA** (far-red photoreceptor): protects against light-induced inhibition.
- **HY5**: downstream light-signaling factor, protects explants via anthocyanin accumulation.
