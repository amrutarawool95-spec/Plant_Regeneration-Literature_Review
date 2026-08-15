# Plant Regeneration â€” Literature Review

A structured literature review of:

> Ikeuchi, M., Ogawa, Y., Iwase, A. & Sugimoto, K. (2016). **Plant regeneration: cellular origins and molecular mechanisms.** *Development* 143, 1442â€“1451. [doi:10.1242/dev.134668](https://doi.org/10.1242/dev.134668)

This repo breaks the review paper down into a readable summary plus a searchable gene/pathway glossary, intended as a reference for anyone working on plant developmental biology, regeneration, or comparative genomics of regeneration-related genes.

## Contents

| File | Description |
|---|---|
| [`literature-review.md`](./literature-review.md) | Full structured review â€” evolutionary diversity of regeneration, cellular origins, the three core molecular pathways (shoot organogenesis, root organogenesis, somatic embryogenesis), epigenetic control, natural genetic variation/QTLs, developmental & environmental constraints, applied biotech relevance, and a critical assessment with open questions. |
| [`gene-glossary.md`](./gene-glossary.md) | Quick-reference tables of every gene, hormone, and epigenetic regulator discussed in the paper, organized by pathway, for fast lookup. |

## Summary

Plant regeneration relies on **cellular plasticity** â€” differentiated or undifferentiated cells re-specifying their developmental fate in response to wounding, hormones, or stress. The review traces this from single-celled algae through mosses and liverworts to seed plants, then focuses on the three best-characterized regeneration programs in Arabidopsis:

1. **De novo shoot organogenesis** â€” WIND â†’ PLT â†’ CUC â†’ WUS/PIN1/STM
2. **De novo root organogenesis** â€” auxin â†’ WOX11/WOX12 â†’ LBD16/LBD29 â†’ WOX5
3. **Somatic embryogenesis** â€” WUS â†’ LEC1/LEC2/FUS3 + AGL15 â†’ auxin/GA/ABA rebalancing

Regenerative competence is kept epigenetically repressed under normal conditions (via PRC2, histone deacetylases, and DNA methylation) and is unlocked by wounding, stress, or hormone signaling. Natural genetic variation (e.g., `RPK1`, ferredoxin-nitrite reductase in rice, `Rg1` in tomato) shows this capacity is a tunable, breedable trait â€” directly relevant to improving transformation efficiency in recalcitrant crop species.

See `literature-review.md` for the full breakdown, including figures-to-text mapping and open questions flagged by the authors.

## Citation

```bibtex
@article{Ikeuchi2016,
  author  = {Ikeuchi, Momoko and Ogawa, Yoichi and Iwase, Akira and Sugimoto, Keiko},
  title   = {Plant regeneration: cellular origins and molecular mechanisms},
  journal = {Development},
  year    = {2016},
  volume  = {143},
  pages   = {1442--1451},
  doi     = {10.1242/dev.134668}
}
```

## Notes

This review was compiled for personal literature-review/research reference purposes. All summaries are paraphrased from the original article; refer to the [original paper](https://doi.org/10.1242/dev.134668) for full details, figures, and the complete reference list.
