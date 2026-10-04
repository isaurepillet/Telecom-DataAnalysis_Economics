# Research Networks in Economics — Data Analysis & Visualisation

**Collaborative academic project in Data Analysis / Data Visualisation**

This repository contains a collaborative analysis of **research networks in economics** using data collected from RePEc and related academic sources.

## Project scope

The project builds researcher- and paper-level datasets to study patterns in academic economics. The workflow combines publication metadata, **JEL classifications**, author affiliations and gender-related information, then uses descriptive statistics, network analysis and clustering to explore the structure of the research community.

## Main workflow

The repository contains notebooks and scripts for:

- extracting and processing JEL codes from RePEc records;
- collecting and harmonising author affiliations;
- matching author, affiliation and publication datasets;
- descriptive analysis and data visualisation;
- gender-related analysis, including an R regression script;
- network and cluster analysis of researchers and institutions.

## Main files

- **`Analysis_Final_Data.ipynb`** — analysis of the consolidated dataset;
- **`JEL-code-new.ipynb`** — processing of JEL classifications;
- **`Scrapping-auteur-affiliation.ipynb`** — collection of author affiliations;
- **`mergedata_set.ipynb`** and **`isaure merge.ipynb`** — dataset matching and consolidation;
- **`processing_and_cluster_study_p30.ipynb`** — network / cluster analysis;
- **`Gender Analysis.ipynb`** and **`regression.R`** — gender-related analysis.

## Tools and methods

Python · R · pandas · Jupyter · web scraping · data cleaning · entity matching · network analysis · clustering · data visualisation

## Collaboration

This repository is a fork of the original collaborative course repository. The analysis was produced as a group project; the commit history preserves the individual contributions of the collaborators.
