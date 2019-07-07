# GPSR Commands Dataset [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3244800.svg)](https://doi.org/10.5281/zenodo.3244800)

A dataset of robot commands and their logical representations. Generated data is from the [command generator](https://github.com/kyordhel/GPSRCmdGen) used for the _General-Purpose Service Robot_ task in the 2018 RoboCup@Home competition. Paraphrased data was collected from crowd workers.

Splits on both commands and logical forms are provided. Splits across generated and paraphrased datasets are parallel so that they can be combined without further processing. Note that generated data is anonymized; entities are replaced with tokens describing their class. Paraphrased data is not anonymized.

For further details and baseline suggestions, please check out our paper, [Neural Semantic Parsing with Anonymization for Command Understanding in General-Purpose Service Robots](https://arxiv.org/abs/1907.01115). 

Code for this paper, including the crowd-sourcing interface are available [here](https://github.com/nickswalker/gpsr-command-understanding).