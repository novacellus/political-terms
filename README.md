# Latin Socio-political Terms Across Centuries: Tracing Sense Evolution with Distributional Semantics

The repository contains code for 2 studies in distributional semantics tracing evolution and distribution of Latin socio-political terms presented at:
* LVLT 22: Barbara McGillivray and Krzysztof Nowak, "Tracing the semantic change of socio-political terms from Classical to early Medieval Latin with computational methods"
* ICLL 23: Krzysztof Nowak and Barbara McGillivray, "Investigating dimensions of lexical-semantic variation in Latin with distributional methods"

The code here was authored by KN (if no mistake). For the up-to-date version of Barbara's code and the current state of LatinISE, see: https://github.com/BarbaraMcG

For both studies (prefixed lvlt22_ and icll23_) files contain code:

## Aligned Time Spans
* `lcollocs-aligned.ipynb`: syn- and diachronic collocation overlap
* `distribution-aligned.ipynb`: word frequency
* `count-aligned.ipynb`: cosine similarity with count vectors

## Study: Alternative Time Spans
* `collocs.ipynb`: syn- and diachronic collocation overlap
* `distribution.ipynb`: word frequency
* `count.ipynb`: cosine similarity with count vectors

## Configuration, Utils
* `lvlt22_count_experiments-exp.ipynb`: notebook for testing various count vectors setups
* `lvlt22_count_experiments.py`: script for testing various count vectors setups (less prone to system crashes due to memory issues than the notebook version)
* `lvlt22_bins.ipynb`: testing time slices
* `semantic_change.ipynb`: code for detecting semantic change
* `data/`: a set of data manipulation classes the notebooks in this folder depend on
* `out/`: output dir
* `out/models`: pickled models
* `htmls/`: HTML exports of the Jupyter notebooks
