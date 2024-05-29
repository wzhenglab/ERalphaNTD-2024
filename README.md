# Sequence analysis for "The sequence-structure-function relationship of intrinsic ERalpha disorder"

This repository contains Python code and raw data for reproducing the sequence analysis results presented in the manuscript "The sequence-structure-function relationship of intrinsic ERalpha disorder".

The `seq_data` directory contains the sequence data of the 3 datasets we used: IDR, folded protein and NTD.
`feature_calculation.ipynb` calculates the sequence features (Fraction of Charged Amino Acids and Sequence Hydrophobic Patterning). The pre-calculated results are stored in `feature_data`.
`plot.ipynb` plots the contour plots for the 3 datasets as shown in the manuscript.

IDR database includes 28,058 sequences curated in Tesei et. al. Nature, 626: 897-904 (2024). Folded database includes 2,360 sequences curated in Chen et. al. Acta Crystallogr D Biol Crystallogr 66: 12-21 (2010), excluding folded structures with multiple chains.
