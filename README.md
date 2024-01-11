# Peaklist-to-heatmap
<p align="justify">This repository contains the code and the MZmine3 output files required to reproduce heatmaps used in our work related to manzamine alkaloids biosynthesis entitled "Baldwin and Whitehead's Manzamine Alkaloids Biosynthetic Hypothesis Would Imply a Finely Tuned Reactivity of C<sub>3</sub> Unit, an HTE Approach". MZmine3 batch files and probes MS/MS spectra (keramaphidin B scaffold and <i>iso</i>-scaffold) related to our work are also provided but they are not needed to use the code.</p>

## Description
<p align="justify">This code written in Python enables to convert annotation and quantification table files (.csv) generated by MZmine3 from 96 individual multicomponent reactions into cosine score and relative abundance-based heatmaps according to a single annotated compound. A filtration setting based on the cosine score is also available in the script to adjust the level of confidence. The code was developed to deal with high-throughput experimentation data where three reaction condition parameters have been modified (e.g., catalyst, solvent, reagent addition order). Therefore, heatmaps include a specific layout designed for our work. However, the script can be easily modified and serve as a starting point to be applied to other cases or find another application for organic chemists.</p>
