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
Contains code used for source localization experiments
* /regularization_experiments → grid search for regularization experiments
* /training_config → configuration file for experiments in ./training_pipeline.py

# /prediction
Contains code used for experiments with MOLENE and NOAA datasets for timeseries forecasting
* /train_utils → handy functions used throughout the experiments
* /pred_utils → handy functions to deal with the NOAA and MOLENE datasets
* /evaluation → handy functions for evaluating timeseries predictions
* /MOLENE → dataset + code for processing, analyzing, training and evaluating the models
* /NOAA → dataset + code for processing, analyzing, training and evaluating the models

# /earthquakes
Contains the material for the earthquake study.
* /code/regions/precursor_based/OriginalProblem → multiclass classification for earthquakes (contains code to crawl, label, clean, and process the earthquake data)
* /code/regions/percursor_based/OAA → binary problem one Against all
* /quakes_util → useful functions used in the experiments with earthquakes, such as radius- based metrics.

# /datasets
Contains the synthetic data for the source localization experiment. Can be easily recreated using the python script in the /data_generation folder.

# /architectures
Contains code defining the different architectures (LSTM, GRNN,GTCNN)


