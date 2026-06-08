# Behavioural Forma Mentis Networks (BFMN)

R scripts for constructing and analysing Behavioural Forma Mentis Networks (BFMNs) from semantic association and affective data. Creates group-level and individual-level networks, and visualizes semantic frames for cue words.

## Overview

The BFMN methodology (Brian & Stella, 2023) integrates semantic associations with emotional valence information to investigate the cognitive and affective organisation of concepts.

The repository includes workflows for:
* Constructing group-level BFMNs
* Constructing individual-level BFMNs
* Assigning emotional valence to concepts
* Identifying emotional network structures
* Computing network metrics
* Visualising semantic-emotional networks

## Files

### PhD_EntireFMN.Rmd

Constructs group-level Behavioural Forma Mentis Networks from aggregated participant data.

Main outputs include:

* Network structure
* Emotional valence assignment
* Network metrics
* Visualisations

### PhD_IndividualFMNs.Rmd

Constructs participant-specific Behavioural Forma Mentis Networks.

Main outputs include:

* Individual semantic-emotional networks
* Individual network metrics
* Comparative analyses across participants

## Requirements

Required R packages are listed within the scripts and include:

* igraph
* tidyverse
* readxl
* ggraph
* tidygraph

## Input Data

The scripts require semantic association data and emotional valence information organised in tabular format.

An example dataset is provided ("PhD_FMN_Data.xlsx").

## Methodological Background

Behavioural Forma Mentis Networks combine semantic relationships between concepts with affective information to characterise cognitive representations (Brian & Stella, 2023; Haim et al., 2026a; Haim et al., 2026b).
For theoretical and methodological details, please consult the publications listed below.

## Citation
* Brian, K., & Stella, M. (2023). Introducing mindset streams to investigate stances towards STEM in high school students and experts. Physica A: Statistical Mechanics and its Applications, 626, 129074.
* Haim E., Van den Bergh L., Marinazzo D., Siew C., Stella M. (2026a). Cognitive networks highlight differences and similarities in the STEM mindsets of human and LLM-simulated trainees, experts and academics. Journal of Complex Networks, 14(2).
* Haim, E., Haim, K., Beaty, R.E., Siew, C.S.Q., Stella, M. (2026b). Introducing multiplex semantic networks as multifaceted representations of creative associative knowledge across multilingual samples. arXiv.

## License

MIT License.
