# PD-L1 nanobody design — literature collection

Collected: 2026-11-18. Public literature and official code only.

## Naming

`YYYY-MM-DD—Venue—Model` uses the **collection date**. The onboarding naming instruction does not specify whether date means collection or publication; publication dates and manuscript versions are recorded separately. `Preprint` denotes an unreviewed report, not a journal abbreviation; `CellDiscov` abbreviates Cell Discovery. Suffixes distinguish Main, Supplement, Code and PDB sources.

## Reading index

| Record | Scope | Main paper | Supplement | Official code / structure |
|---|---|---|---|---|
| [2026-11-18—Preprint—BoltzGen](2026-11-18—Preprint—BoltzGen.md) | Core design method | [Paper](https://hannes-stark.com/assets/boltzgen.pdf) | Embedded in paper PDF | [Code](https://github.com/HannesStark/boltzgen) |
| [2026-11-18—Preprint—PXDesign](2026-11-18—Preprint—PXDesign.md) | Core design method | [Paper](https://protenix.github.io/pxdesign/technical_report.pdf) | Embedded in paper PDF | [Code](https://github.com/bytedance/PXDesign) |
| [2026-11-18—Nature—RFantibody](2026-11-18—Nature—RFantibody.md) | Supporting method / experimental reference | [Paper](https://www.nature.com/articles/s41586-025-09721-5) | [Supplement](https://static-content.springer.com/esm/art%3A10.1038%2Fs41586-025-09721-5/MediaObjects/41586_2025_9721_MOESM1_ESM.pdf) | [Code](https://github.com/RosettaCommons/RFantibody) |
| [2026-11-18—Preprint—Boltz-2](2026-11-18—Preprint—Boltz-2.md) | Supporting method / experimental reference | [Paper](https://jeremywohlwend.com/assets/boltz2.pdf) | Embedded in paper PDF | [Code](https://github.com/jwohlwend/boltz) |
| [2026-11-18—CellDiscov—KN035](2026-11-18—CellDiscov—KN035.md) | Supporting method / experimental reference | [Paper](https://www.nature.com/articles/celldisc20174) | [Supplement](https://static-content.springer.com/esm/art%3A10.1038%2Fcelldisc.2017.4/MediaObjects/41421_2017_BFcelldisc20174_MOESM126_ESM.pdf) | [5JDS](https://www.rcsb.org/structure/5JDS); no dedicated code repository identified |

## Notebook

[PD-L1 Nanobody Design — Literature](https://notebook.google.com/notebook/493de24d-55da-4579-9205-5f1c83d15872)

This GitHub collection is a curated source-link index, not a mirror of third-party PDFs or source-code repositories. Notebook sources contain the three report PDFs, two separate supplementary PDFs, four official repository pages, the 5JDS record and publisher-page text for RFantibody and KN035. Publisher-page text preserves the readable article and captions but not figure images; refer to the original article/PDF for figures. Failed direct publisher imports may remain visibly flagged in Notebook; use the named readable text sources instead.

## Interpretation limits

Computational confidence is not experimental binding affinity or proof of blockade. Compare metrics only after matching predictor, conditioning, construct, residue mapping and alignment definitions. Verify VHH support separately from generic protein-binder capability. A literature listing is not evidence that any model has been run.
