# ssProteomics-workflow

**Manuscript title:**  
Single-subject Proteomic Signatures in Alzheimer’s Disease Reflect Clinical Phenotypes and Distinguish Asymptomatic from Symptomatic Cases

**Authors:**  
Avijit Podder¹, Yi Juin Liew¹, Greg A. Cary², Gregory W. Carter¹², Asli Uyar¹ 

¹ The Jackson Laboratory for Genomic Medicine, Farmington, CT, USA
² The Jackson Laboratory, Bar Harbor, ME, USA 

**Corresponding author:**  
Gregory W. Cartern (gregory.carter@jax.org); Asli Uyar (asli.uyar@jax.org)


## Overview

Analysis workflows and rendered HTML reports supporting the proteomics results
presented in the associated manuscript.

This repository provides transparent access to the analysis logic, code structure,
and outputs used in the study, including TMT-based proteomics processing, differential expression analysis, 
pathway- and subdomain-level profiling, graph-based clustering, and clinical
correlation analyses.

---

## 🔗 Rendered analysis workflows

The rendered HTML workflows can be browsed online at:

**https://avijitpodder-ap.github.io/ssproteomics-workflow/**

Each section corresponds to a major component of the analysis pipeline and includes
embedded figures and code blocks.

---

## 📂 Repository structure

Each `sectionX/` directory contains:
- a rendered `.html` workflow report
- the corresponding `.Rhtml` source file
- a `figure/` folder with generated figures

---

## 🔬 Data availability

The input proteomics data used in these analyses were obtained from the
ROSMAP study and are subject to controlled access and data-use agreements.
As such, raw input data files are **not** included in this repository.

File paths in the source code reflect the authors’ local computing environment
and are provided for transparency and documentation of the workflow.

---

## ♻️ Reproducibility notes

- The HTML files are static, rendered outputs and can be viewed without any
  additional software.
- The `.Rhtml` files document the full analysis logic but may require access
  to controlled datasets and appropriate R package versions to be re-executed.
- Package versions and computational parameters are described within the
  individual workflow reports.

---

## 📜 License

This repository is made available for academic and non-commercial use.
Unless otherwise stated, code is released under the MIT License.

---

## 📖 Citation

If you use or reference this workflow, please cite the associated manuscript.
A DOI-linked archival version of this repository may be added upon publication.

