# PLC Forensics — Supplementary Materials

This repository hosts the supplementary artefacts for the thesis:

> **“A PLC-centric Digital Forensic Readiness Framework for Industrial Control Systems.”** (2025) — Feras Shahbi, University of Bristol.

## What’s inside

- **`/fvf-assessment-tool/`** — Interactive FVF assessment tool (HTML, with tooltips, exports, validation and reporting).  
- **`/sand-attack-trees/`** — Sequential AND (SAND) attack‑tree models used to inform and instantiate playbook slices (e.g., reconstructed *Stuxnet* and *HARVEY* sequences), as PDFs and tab‑indented text files.  
- **`/plc-digital-forensic-readiness-playbooks/`** — PLC Digital Forensic Readiness Playbooks (PDF‑RP) provided as BPMN 2.0 `.bpmn` and `.xml` plus exported `.pdf` diagrams for review and import into **Camunda Modeler**.

> Each folder contains a small README with usage notes.

## Quick start

1. **Browse folders** above.  
2. For the **FVF assessment tool**, open `fvf_assessment_interface_v1.html` locally in your browser (Chrome/Edge/Firefox). No server required.  
3. For **playbooks**, import `.bpmn` into *Camunda Modeler* (or any BPMN 2.0 tool); exported PDFs are provided for quick inspection.

## Folder map

```
plc-forensics-supplementary-materials/
├─ fvf-assessment-tool/
│  ├─ fvf_assessment_interface_v1.html                # The interactive user interface 
├─ sand-attack-trees/
│  ├─ stuxnet/                  # PDFs and tab-indented *.txt
│  ├─ harvey/                   # PDFs and tab-indented *.txt
│  └─ README.md
├─ plc-digital-forensic-readiness-playbooks/
│  ├─ bpmn/                     # *.bpmn models
│  ├─ xml/                      # *.xml exports (if separate)
│  ├─ diagrams/                 # *.pdf / *.png exports
│  └─ README.md
├─ CITATION.cff
├─ LICENSE-CODE (MIT)
├─ LICENSE-CONTENT (CC BY 4.0)
└─ .gitignore
```

## How to cite

Please cite the thesis (see `CITATION.cff`) and, where applicable, the repository release DOI once archived (e.g., via Zenodo).

## Licences

- **Code** (e.g., HTML/JS/CSS for the FVF tool): see `LICENSE-CODE`.  
- **Content** (e.g., diagrams, models, PDFs, text exports): see `LICENSE-CONTENT`.

---

Maintainer: Feras Shahbi — University of Bristol
