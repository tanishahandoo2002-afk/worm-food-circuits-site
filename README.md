# Worm Food Circuits

Findings page for a computational analysis of feeding, food encounter and longevity wiring in *C. elegans*.

**View it:** https://tanishahandoo2002-afk.github.io/worm-food-circuits-site/

This is a student research project and has not been peer reviewed. Its findings are computational predictions from public data; no lifespan was measured.

This repository holds only the published page, `index.html`, a single self-contained file that bundles its summary tables and the [d3](https://d3js.org) library (ISC licence).

The brain-activity charts (two heatmaps, an MC activity trace and the responders chart) show processed data from the Flavell lab's recordings, credited on the page. The source datasets state no licence, so we are asking the lab for permission to show them, and will remove them if asked.

## Data sources

- Atanas & Kim et al. (2023) *Cell*, whole-brain recordings ([paper](https://doi.org/10.1016/j.cell.2023.07.035)).
- Dag et al. (2023) *Cell*, food-encounter recordings ([data](https://zenodo.org/records/19414639)).
- Cook et al. (2019) *Nature* and Witvliet et al. (2021) *Nature*, synaptic connectomes.
- Ripoll-Sánchez et al. (2023) *Neuron* and Bentley et al. (2016) *PLoS Computational Biology*, neuropeptide links.

Connectome data were read through the OpenWorm ConnectomeToolbox. The MIT licence covers this project's own code and page, not the source datasets.

## AI use

An AI assistant (Claude) wrote and ran the analysis code, drafted the neuron lists and proposed the analysis decisions. Tanisha Handoo and a second reviewer accepted the decisions and lists.
