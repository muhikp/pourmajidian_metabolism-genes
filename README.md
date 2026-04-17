# Mapping energy metabolism systems in the human brain
This repository contains code and data used in "Mapping energy metabolism systems in the human brain", available on [bioRxiv](https://doi.org/10.1101/2025.03.17.643763). 

Now published in [PLOS Biology](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3003619).

## scripts
The [scripts](scripts/) folder conatins all the scripts required to run the analyses described in the manuscript.

## data
To be able to run the scripts, please download the following data

- [BrainSpan dataset](https://www.brainspan.org/static/download.html): download "RNA-Seq Gencode v10 summarized to exons" and "Exon microarray summarized to genes"

The [data](data/) folder includes:
- Structural classes and functional network assignments (Mesulam, Von Economo-Koskinas and Yeo-Krienen) for Schafer-400 and Schaefer-100 parcellations.
- Structural and functional connectivity matrices.
- Cell- and Layer-specific marker genes.
- All other maps used in the analysis including group-average PET and MEG maps and functional connectivity gradients can be retrieved using the neuromaps package with code provided in [scripts](scripts/s14_prepare_brain_maps.py).

## results
The [results](results/) folder includes outputs generated from the scripts, including the energy expression matrices and mean expression maps.
