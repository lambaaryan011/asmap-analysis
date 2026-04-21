# ASmap Competency Test – Analysis

![Status](https://img.shields.io/badge/status-completed-brightgreen)
![Project](https://img.shields.io/badge/project-ASmap-blue)
![Program](https://img.shields.io/badge/program-Summer%20of%20Bitcoin-orange)
![Language](https://img.shields.io/badge/language-Python-yellow)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

##  Overview
This project is part of the ASmap competency test for the Summer of Bitcoin program.

The goal was to:
- Generate a custom ASmap file using Kartograf
- Compare it with a baseline ASmap from a previous collaborative run
- Analyze the differences using available tooling

---

##  Methodology

### 1. ASmap Generation
- Used Kartograf to generate a new ASmap file
- Followed standard data sources used in collaborative runs

### 2. Baseline Data
- Downloaded an older ASmap file from the `asmap-data` repository
- Used it as a reference for comparison

### 3. Comparison
- Used diff tools available in Bitcoin Core / asmap-tool
- Compared:
  - IP prefix coverage
  - ASN mappings
  - Structural differences

---

##  Key Observations

- Differences were observed in ASN assignments for certain IP ranges
- Some mappings changed due to updated routing data
- The generated ASmap showed slight variations in coverage compared to the baseline

---

##  Expectations vs Reality

### Expected:
- Minor differences due to updated datasets
- Mostly similar structure between maps

### Observed:
- Some unexpected ASN changes
- More variation than anticipated in certain prefixes

---

##  Challenges Faced

- Limited clarity in documentation for certain tools
- Understanding diff outputs required manual interpretation
- Tooling could be improved for better visualization

---

##  Suggestions / Improvements

- Better documentation for ASmap comparison tools
- Visualization dashboard for easier analysis
- Automated diff summaries for quicker insights

---

##  Conclusion

This exercise helped in understanding how ASmaps evolve over time and how they impact peer selection in Bitcoin nodes. It also highlighted the need for better tooling and analysis methods for collaborative improvements.

---
