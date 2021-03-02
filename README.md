# DSLW-Code

This repository contains the PyTorch codes for the paper:

E. Isufi and G. Mazzola, Graph-Time Convolutional Neural Networks, IEEE Data Science and Learning Workshop (DSLW), Toronto, Ontario, Canada, June 2021.

Parts of this code are taken verbatim from the GNNs library available [here](https://github.com/alelab-upenn/graph-neural-networks). The following is a description of the functions contained in the different folders used to generate the results in the paper. A cured and more explained version will be uploaded in the future.

# /utils
* /data_utils → code used for the data generation for the source localization experiments
* /graph_utils → code used for graph generation and graph composition within GTCNN model
* /misc_utils → handy functions used throughout the code
* /plot_utils → functions used for plotting charts
* /src_loc_utils → re-adaptation of functions from [GNN_repository](https://github.com/alelab-upenn/graph-neural-networks)

# /training
* /regularization_experiments → grid search for regularization experiments
* /training_config → configuration file for experiments in ./training_pipeline.py


