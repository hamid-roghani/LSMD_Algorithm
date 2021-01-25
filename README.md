# LSMD_Algorithm
LSMD: A fast and robust local community detection starting from low degree nodes in social

This is the Matlab implementation of LSMD: A fast and robust local community detection starting from low degree nodes in social.

The original paper is available in: https://www.sciencedirect.com/science/article/abs/pii/S0167739X2030724X

This code implements LSMD algorithm in MATLAB 2017

We have used neighboring list structure as the input file for algorithm. The execution of the LSMD is so simple.To execute the code, it is needed to put extracted folder of"datasets.rar" into one folder with the extracted source codes of "LSMD_CommunityDetection_Algorithm.rar". Then open "main_algorithm.m" to write dataset name to start execution. In some datasets it is not necessary to execute merge step which it can be contoroled by "merge_falg" before execution. The output of the algorithm is label array of nodes which is writen in "results" folder.


Names of datasets are as follows and are available in "datasets" folder.

# Datasets:

karate

Dolphins

Polbooks

Football

email

email_enron

netscience

power

ca_grqc

collaboration

ca_hepth

PGP

condmat_2003

condmat_2005

DBLP

Amazon
