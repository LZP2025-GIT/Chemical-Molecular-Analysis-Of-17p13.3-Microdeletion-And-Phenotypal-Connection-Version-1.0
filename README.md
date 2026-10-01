# Genome Research: 17p13.3 Microdeletion

**Genomic and Molecular Analysis of a 17p13.3 Microdeletion and Its Candidate Visual-Neurological Mechanisms**

Author: **Zachariah P. Laing**  
ORCID: **0009-0004-8765-4601**  
Frozen first-pass research record: **Version 1.0**  
Repository preparation date: **2026-10-01**

## Overview

This repository preserves a six-phase research project examining the biological consequences of a heterozygous 17p13.3 deletion and whether available evidence supports a mechanistic connection to visual-neural dysfunction, seizure susceptibility, photoparoxysmal response, or epileptic photosensitivity.

The project is intentionally conservative about causality. It separates genomic disruption from dosage consequences, molecular mechanisms, expression opportunity, cellular phenotypes, developmental effects, visual-system physiology, seizure-related physiology, and clinical phenotype. Evidence at an earlier layer is not treated as proof of a later layer.

## Fixed genomic reference

- Assembly: **GRCh37/hg19**
- Interval: **chr17:1,411,408–1,841,103**
- State: **heterozygous deletion**
- Nominal span: **429,696 bp**
- Boundary-intersected protein-coding genes: **INPP5K** and **RTN4RL1**
- Minimum affected loci: **17**

Protein-coding loci: INPP5K, PITPNA, SLC43A2, SCARF1, RILP, PRPF8, TLCD2, WDR81, SERPINF2, SERPINF1, SMYD4, RPA1, RTN4RL1.

Noncoding loci: PITPNA-AS1, MIR22HG, MIR22, RN7SL105P.

## Frozen first-pass conclusion

The deletion is biologically consequential and contains plausible mechanisms involving retinal support, membrane/phosphoinositide biology, trafficking, stress and DNA-damage response, neuronal development, and network organization. The evidence currently favors a **distributed functional-reserve model** over a single-gene photosensitivity mechanism.

The project does **not** establish that this exact heterozygous CNV directly causes epileptic photosensitivity. Major unresolved links include genotype-specific retinal physiology, retinal temporal coding, lateral geniculate physiology, V1 flicker responses, cortical excitation/inhibition balance, frequency entrainment, phase locking, long-range propagation, photoparoxysmal response, and visually triggered seizures.

## Repository map

```text
Genome-Research-17p13.3/
├── README.md
├── LICENSE
├── CITATION.cff
├── CHANGELOG.md
├── CONTRIBUTING.md
├── REPOSITORY_MAP.md
├── .gitignore
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── erratum.yml
│   │   └── evidence_update.yml
│   └── pull_request_template.md
├── phases/
│   ├── phase-01/
│   ├── phase-02/
│   ├── phase-03/
│   ├── phase-04/
│   ├── phase-05/
│   └── phase-06/
├── references/
├── appendices/
├── summaries/
├── release/
├── metadata/
└── scripts/
```

## Phase summary

### Phase 1 — Structural locus characterization

Defined the deletion and affected loci. Eleven protein-coding genes are fully encompassed; INPP5K and RTN4RL1 intersect the boundaries. Under the reported-coordinate model, approximately 49.6% of INPP5K amino-acid-coding sequence and approximately 99% of RTN4RL1 CCDS sequence are affected. Exact nucleotide junctions, transcript fate, NMD, protein abundance, and tissue-specific dosage remain unresolved.

### Phase 2 — Molecular synthesis

Identified mechanistic themes involving phosphoinositides, lipid transfer, membrane composition, endosomal/lysosomal trafficking, retinal trophic biology, RNA splicing, DNA replication/repair, neuronal development, immune clearance, and related systems. The evidence supported a multi-gene architecture but not uniform 50% functional loss, a single causal gene, or demonstrated synergy.

### Phase 3 — Expression and spatiotemporal opportunity

Found the clearest adult retinal/RPE localization around INPP5K, PITPNA, and SERPINF1, with broad retinal expression for PRPF8 and a preliminary TLCD2 cone signal. The project did not find a convincing magnocellular-specific deletion signature in dLGN or a deletion-wide V1-specific program. Expression was interpreted as biological opportunity, not dysfunction.

### Phase 4 — Dosage, perturbation, physiology, and adjudication

The evidence favored reduced or altered reserve, maintenance, recovery, and stress resilience more strongly than direct sensory amplification. Retinal and neural perturbation data did not establish a hyperresponsive retina or generalized hyperexcitability. The exact CNV remained untested for the key cortical and photic physiology required to establish epileptic photosensitivity.

### Phase 5 — Evidence integration and robustness

Phase 5 formalized evidence layers, competing models, missingness, perturbation equivalence, sensitivity analysis, and simulation-based methodological checks. It retained the distributed-reserve model while emphasizing that photosensitivity sits downstream of several unmeasured causal layers. See `phases/phase-05/README.md` for the archival status of the Phase 5 standalone record.

### Phase 6 — Project conclusion and freeze

Closed the first in-silico pass. The frozen classification is a biologically consequential CNV and a mechanistically plausible candidate modifier of visual-neural and epileptogenic reserve. Direct causation of epileptic photosensitivity remains unresolved.

## Canonical release

The complete APA 7 formatted project is preserved as:

- `release/Genome_Research_Complete_Project_APA7_v1_0.pdf`
- `release/Genome_Research_Complete_Project_APA7_v1_0.docx`

The five-page nontechnical summary is in `summaries/`.

## Reproducibility and provenance

This repository preserves the frozen documents and metadata currently available. It does not fabricate missing raw datasets, scripts, breakpoint sequences, or experimental results. A SHA-256 manifest is provided in `metadata/MANIFEST.sha256` for file-integrity verification.

For future revisions, do not silently overwrite frozen conclusions. Use an erratum, a formally reopened analysis, or a new version. Contradictory and null findings should remain visible in the record.

## License

Unless otherwise noted for third-party quoted or cited material, this repository's original text and project documentation are licensed under **Creative Commons Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)**. See `LICENSE`.
