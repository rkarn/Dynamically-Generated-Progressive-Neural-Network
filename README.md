# Dynamically-Generated-Progressive-Neural-Network

This repsitory contains the source code to reproduce the results of paper:

`Karn, Rupesh Raj, Prabhakar Kudva, and Ibrahim Abe M. Elfadel. "Dynamically generated compact neural networks for task progressive learning." In 2020 IEEE International Symposium on Circuits and Systems (ISCAS), pp. 1-5. IEEE, 2020.`

It contains jupyter nootebook which is self-explanatory for different datasets.

This work uses synaptic weight consolidation methodology implemented in 

    https://github.com/ganguli-lab/pathint
    
    Install the python libraries mentioned there.
    
    To run the congestion detection code, please perform following steps:
    1. git clone https://github.com/ganguli-lab/pathint
    2. cd pathint/fig_split_mnist/
    3. Copy all the ipynb files in "pathint/fig_split_mnist/" directory.

UNSW-NB15 dataset can be downloaded from

    https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/

    Download the UNSW_NB15_training-set.csv and UNSW_NB15_testing-set.csv files.
    
AWID Dataset can be downloaded from 

    http://icsdweb.aegean.gr/awid/download.html 
    
    Download the AWID-ATK-R-Trn and AWID-ATK-R-Tst files. 
    
    Description links:     
    http://icsdweb.aegean.gr/awid/features.html 
    http://icsdweb.aegean.gr/awid/attributes.html
    http://icsdweb.aegean.gr/awid/draft-Intrusion-Detection-in-802-11-Networks-Empirical-Evaluation-of-Threats-and-a-Public-Dataset.pdf
    
MNIST dataset can be downloaded from: 

    https://chromium.googlesource.com/external/github.com/tensorflow/tensorflow/+/r0.7/tensorflow/g3doc/tutorials/mnist/download/index.md
