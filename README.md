# Mapping the UK Circular Economy Research Ecosystem: Inputs and Outputs

This repository contains the code and supplementary materials supporting my MSc Data Science dissertation at Durham University.

## Project Overview

This study maps the UK circular economy research ecosystem by examining:

- the distribution of UK circular economy research funding across disciplines and organisations;
- the disciplinary characteristics of research outputs;
- the alignment between funded projects and their subsequent research outputs; and
- changes in interdisciplinarity between the project and publication stages.

The analysis integrates data from the UKRI Gateway to Research (GtR), OpenAlex and supplementary Scopus records.

## Methods

The analysis includes:

- data cleaning and integration;
- disciplinary mapping;
- multi-label text classification using TF-IDF and logistic regression;
- descriptive funding analysis;
- OLS regression with HC3 robust standard errors;
- project-output disciplinary alignment analysis;
- permutation testing; and
- interdisciplinarity analysis.

## Repository Structure

- `notebooks/` – Python/Jupyter notebooks used for data processing and analysis
- `data/` – selected processed data and disciplinary crosswalk files
- `results/` – selected analytical outputs and statistical results

## Data Sources

The study uses data from:

- UKRI Gateway to Research (GtR)
- OpenAlex
- Scopus (supplementary bibliographic source)

Raw Scopus records are not redistributed in this repository because of database licensing restrictions.

## Dissertation

MSc Data Science Research Project  
Durham University  
2026
