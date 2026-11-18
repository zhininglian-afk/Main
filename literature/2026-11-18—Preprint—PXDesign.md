# 2026-11-18—Preprint—PXDesign

**Title:** PXDesign: Fast, Modular, and Accurate De Novo Design of Protein Binders

**Collected:** 2026-11-18

**Publication / version:** Inspected author-hosted report identifies Version 3, December 12, 2025. Related bioRxiv v3 was posted December 17, 2025; DOI 10.1101/2025.08.15.670450.

## Sources

- Main paper: https://protenix.github.io/pxdesign/technical_report.pdf
- Supplementary material: Appendices are embedded in the technical report: confidence filtering, hallucination, diffusion, computational benchmarks and wet-lab protocols. Inspect the report revision history before comparing results.
- Official code: https://github.com/bytedance/PXDesign

## Relevance and reading focus

Core comparator for binder design. Read generation and orthogonal confidence filtering. Its protein-binder benchmark is not automatically evidence for a VHH-format output; verify scaffold/CDR constraints in the implementation before describing a nanobody campaign.

## Questions to answer while reading

- Does the available release support the intended VHH scaffold constraints?
- How are Protenix and AF2-IG filters combined?
- How are experimental hit-rate denominators and generation budgets defined?

## Collection status

GitHub stores verified public source links and this reading record. Notebook holds the report PDF with embedded supplementary/appendix material and official repository page. Code pages are reference snapshots, not executable repository clones. No simulation or wet-lab claim is made by this record.
