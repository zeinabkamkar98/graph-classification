# Collection of Graph Classification Datasets and Checking of the Machine Learning Algorithm on Them


## SUMMERY
Graph classification has recently received a lot of attention from arious fields of machine learning because of its practical  pplications in many different domains. Themain problem in this field is various dataset formats. The purpose of this project is to solve this problem and collect known datasets in this field and convert all datasets to a specific format and at the end check a machine learning algorithm on them to estimate the basic accuracy.

## DATA COLLECTION
There are a lot of graph modality datasets that are used in different tasks like graph classification, node classifications, etc . Desired datasets for this project are known datasets that are used in graph classification problems. So we selected the datasets which are referenced in graph classification papers and benchmarks from valid websites like Kaggle, paperswithcodes, linqs, IAM, … . At the end of this step we collected over 200 datasets. The list of the dataset with their related papers, benchmarks and website are in this.

## DATA CONVERT
As you can see in the collected datasets, there are a lot of duplicate datasets. The only difference between them is their format. So we select The most common and complete format and then convert all datasets to the said format.

### List of converted datasets:
-AIDS
-Alchemy_full
-Aspirin
-Benzene
-BZR
-BZR_MD
-COX2
-COX2_MD
-DHFR
-DHFR_MD
-ER_MD
-Ethanol
-FRANKENSTEIN
-Malonaldehyde
-MCF-7
-MCF-7H
-MOLT-4
-MOLT-4H
-Mutagenicity
-MUTAG
-Naphthalene
-NCI1
-NCI109
-NCI-H23
-NCI-H23H
-OVCAR-8
-OVCAR-8H
-P388
-P388H
-PC-3
-PC-3H
-PTC_FM
-PTC_FR
-PTC_MM
-PTC_MR
-QM9
-Salicylic_acid
-SF-295
-SF-295H
-SN12C
-SN12CH
-SW-620
-SW-620H
-Toluene
-Tox21_AhR_training
-Tox21_AhR_testing
-Tox21_AhR_evaluation
-Tox21_AR_training
-Tox21_AR_testing
-Tox21_AR_evaluation
-Tox21_AR-LBD_training
-Tox21_AR-LBD_testing
-Tox21_AR-LBD_evaluation
-Tox21_ARE_training
-Tox21_ARE_testing
-Tox21_ARE_evaluation
-Tox21_aromatase_training
-Tox21_aromatase_testing
-Tox21_aromatase_evaluation
-Tox21_ATAD5_training
-Tox21_ATAD5_testing
-Tox21_ATAD5_evaluation
-Tox21_ER_training
-Tox21_ER_testing
-Tox21_ER_evaluation
-Tox21_ER-LBD_training
-Tox21_ER-LBD_testing
-Tox21_ER-LBD_evaluation
-Tox21_HSE_training
-Tox21_HSE_testing
-Tox21_HSE_evaluation
-Tox21_MMP_training
-Tox21_MMP_testing
-Tox21_MMP_evaluation
-Tox21_p53_training
-Tox21_p53_testing
-Tox21_p53_evaluation
-Tox21_PPAR-gamma_training
-Tox21_PPAR-gamma_testing
-Tox21_PPAR-gamma_evaluation
-UACC257
-UACC257H
-Uracil
-Yeast
-YeastH
-ZINC_full
-ZINC_test
-ZINC_train
-ZINC_val
-DD
-ENZYMES
-KKI
-OHSU
-Peking_1
-PROTEINS
-PROTEINS_full
-COIL-DEL
-COIL-RAG
-Cuneiform
-Fingerprint
-FIRSTMM_DB
-Letter-high
-Letter-low
-Letter-med
-MSRC_9
-MSRC_21
-COLLAB
-MSRC_21C
-Dblp_ct1
-Dblp_ct2
-DBLP_v1
-Deezer_ego_nets
-Facebook_ct1
-Facebook_ct2
-Github_stargazers
-Highschool_ct1
-Highschool_ct2
-IMDB-BINARY
-IMDB-MULTI
-Infectious_ct1-Infectious_ct2
-Mit_ct1
-Mit_ct2
-REDDIT-BINARY
-REDDIT-MULTI-5K
-REDDIT-MULTI-12K
-Reddit_threads
-Tumblr_ct1
-Tumblr_ct2
-Twitch_egos
-TWITTER-Real-Graph-Partia
-COLORS-3
-SYNTHETIC
-SYNTHETICnew
-Synthie
-TRIANGLES

## ML ALGORITHM
The algorithm we used in this step is a simple baseline algorithm for graph classification. Most algorithms on graph classification rely on complex mathematics and require heavy computational power to achieve their best performance. We propose a simpler and faster algorithm based on the spectral decomposition of graph Laplacian to perform graph classification and get a first reference score for a dataset. Here is the code of the algorithm and you can test it on all of the collected graph dataset and get a basic accuracy.
