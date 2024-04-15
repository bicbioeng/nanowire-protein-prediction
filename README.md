# Nanowire protein prediction

This project focuses on developing machine learning models to classify Nanowire (NW) proteins using various features extracted from protein sequences. Furthermore, BINN can implemented to uncover the pathway for NW formation.
## Table of Contents
- [Introduction](#introduction)
- [Files and Datasets](#files-and-datasets)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
  - [Data Preparation](#data-preparation)
  - [Running the Code](#running-the-code)


## Introduction

The details below would help in running the NW clasification model and BINN for pathway analysis.

## Files and Datasets

- `Nanowire_protein_prediction.ipynb`: Python file for the classification of NW protein.
- `BINN.ipy`: Python file for the pathway analysis during NW formation.
- `Merged.fasta`: Dataset containing both positive and negative fasta file for feature extraction.
- `NCBI_doconno.fasta`: Curated NW protein from NCBI.
- `Uniprot_doconno.fasta`: Curated NW protein from Uniprot
- `Negative.fasta`: Negative protein dataset
- `merged_trancriptomics.csv`: Dataset contains transcriptomics data for both NW forming conditions and non-NW forming conditions
- `Pathways_term.tsv`: Contains the parent and child GO term
- `translation_term.tsv`: Translation for gene to their GO term
- `design_matrix.tsv`: Design matrix for transcriptomcis data indicating NW forming condition and non-NW forming conditions

## Requirements

List the prerequisites to run your code:

- Google colab

## Installation

Clone the repository:

\`\`\`bash
git clone (https:[//github.com/bicbioeng/nanowire-protein-prediction].git
\`\`\`


## Usage

### Data Preparation

For running the Nanowire classification

1. Upload Merged.fasta,NCBI_doconno.fasta, Uniprot_doconno.fasta, and Negative.fasta.

For running the Pathway analysis

2. Upload merged_trancriptomics.csv, Pathways_term.tsv, translation_term.tsv, and design_matrix.tsv

### Running the Code

For running the Nanowire classification:

1. Open and run `Nanowire_protein_prediction.ipynb` in Jupyter Notebook or google colab.
    \`\`\`bash
    jupyter notebook Nanowire_protein_prediction.ipynb
    \`\`\`
For running the Nanowire classification:

2. Open and run `BINN.ipynb` in Jupyter Notebook or google colab
    \`\`\`bash
    jupyter notebook BINN.ipynb
    \`\`\`




