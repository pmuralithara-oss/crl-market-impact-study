# Stock Market Reactions to FDA Complete Response Letters

This repository contains replication code and documentation supporting the working paper:

**“Stock Market Reactions to FDA Complete Response Letters:  
Evidence from Deficiency Types, Firm Characteristics, and Tail Risk”**  
Pranav Muralitharan, Anoushka Banerjee (2026)

## Overview
We study stock market reactions to FDA Complete Response Letters (CRLs) using a
hand-collected dataset of regulatory events and standard event-study methods.
The primary outcome is cumulative abnormal returns around CRL issuance dates.

## Repository Structure
- `code/` – data construction, event study, and regression scripts  
- `data/processed/` – analysis-ready datasets (no raw FDA documents)  
- `output/` – figures and tables reported in the paper  
- `replication_notes.md` – methodological notes and assumptions  

## Data Availability
Raw FDA documents and licensed financial data are not redistributed.
Processed datasets are derived from publicly available regulatory records and
commercial financial data sources.

## Replication
Scripts are numbered in execution order. Running all scripts reproduces the
main tables and figures in the paper.

## Quickstart
1. Install dependencies: `pip install -r requirements.txt`
2. Configure paths/keys (if needed): see `code/00_config_template.py`
3. Run scripts in `code/` in numeric order to reproduce outputs in `output/`.

## Contact
Corresponding author: pmuralitharan@umass.edu
