---
layout: page
title: Software
sidebar_link: true
sidebar_sort_order: 5
---
*Cheminformatics and structural biology*
- In silico high throughput molecular screening system based on various docking engines (DOCK, GOLD, Autodock, VINA and GLIDE XP / SP) and a dozen evaluation functions including own solutions.

- Platform for managing and analyzing screening results - [DiSCus](https://github.com/mwojcikowski/discus) [1]. The software allows integration of in silico screen results with experimental results and enables the use of advanced cheminformatic tools. DiSCuS has been designed primarily for the analysis of "big data" i.e. large screening campaigns against many targets. The ability to easily and very quickly manipulate data allows for efficient optimization of computational models correlating the properties of low molecular weight compounds with experimental observations (SAR, QSAR, CoMFA, etc.).

- [RF-Score-VS](https://github.com/oddt/rfscorevs_binary) [3] function is designed to evaluate the results of high-throughput in silico docking. The key innovation is the inclusion of negative results (inactive ligand complexes) into the training set. One of the main results showing the strength of RF-Score-VS is over a 2.2-fold improvement in relation to classical functions, in discrimination between active and inactive substances among 1% of the highest-ranked molecules (the so-called Enrichment Factor - EF1%).

- [ODDT](https://github.com/oddt/oddt) [2], a set of tools and cheminformatic methods integrated under one "Toolkit". Among the many implemented methods, both own and developed by other researchers, there are: analysis of protein-ligand interaction, module for docking and results assessment, a library enabling the design of data-driven high-throughput HTS protocols. The new generation evaluation functions based on machine learning are also implemented (eg RF-Score, RF-Score-VS or NNscore), and machine learning models for creating own scoring functions: random forests, SVM (support vector machines) and artificial networks (single and multilayered) are supported.

- Deep neural network to predict the affinity of compounds based on their three-dimensional complexes - [Pafnucy](https://gitlab.com/cheminfIBB/pafnucy) [4]. This convolution network is able not only to distinguish active compounds from inactive, but also provides affinity value, in contrast to currently available solutions. An important element of our solution is the ability to determine the physicochemical elements of the model that affect the result obtained by the ligand-receptor complex.

- A package for comparing and assessing compounds based on pharmacophore features - [DeCAF](https://bitbucket.org/marta-sd/decaf.git) [5]. DeCAF offers a measure of compounds similarity based on their physico-chemical characteristics, abstracting from their chemical structure. There are also weights in the model that can be manually modified to introduce additional information known to the researcher. DeCAF allows large-scale comparisons of low-molecular compounds, creating extensive pharmacophore alignments, and thus building models for assessing the activity of chemical molecules without knowing the structure of their complexes with the receptor.

- [PLEC](https://github.com/oddt/notebooks/blob/master/PLEC_fingerprints.ipynb) [6], a method to represent ligand-receptor complexes based on local atomic environments. The method allows for very fast and accurate description of the interaction of atoms in complexes, which become the basis for training and optimization of prediction models, e.g. returning binding affinity values. PLEC provides consistent predictive results for various machine learning (ML) models. Even the linear model built using PLEC returns better results than competing solutions such as SIRILID, SPLIF or more advanced evaluation functions like RF.

References:
1. 	Wójcikowski M, Zielenkiewicz P, Siedlecki P. DiSCuS: an open platform for (not only) virtual screening results management. J Chem Inf Model. 2014;54: 347–354.
2. 	Wójcikowski M, Zielenkiewicz P, Siedlecki P. Open Drug Discovery Toolkit (ODDT): a new open-source player in the drug discovery field. J Cheminform. 2015;7: 26.
3. 	Wójcikowski M, Ballester PJ, Siedlecki P. Performance of machine-learning scoring functions in structure-based virtual screening. Sci Rep. 2017;7: 46710.
4. 	Stepniewska-Dziubinska MM, Zielenkiewicz P, Siedlecki P. Development and evaluation of a deep learning model for protein-ligand binding affinity prediction. Bioinformatics. 2018 May 10
5. 	Stepniewska-Dziubinska MM, Zielenkiewicz P, Siedlecki P. DeCAF-Discrimination, Comparison, Alignment Tool for 2D PHarmacophores. Molecules. 2017;22. doi:10.3390/molecules22071128
6. 	Wójcikowski M, Kukiełka M, Stepniewska-Dziubinska MM, Siedlecki P. Development of a Protein-Ligand Extended Connectivity (PLEC) fingerprint and its application for binding affinity predictions. Bioinformatics. 2018 Sep 8.
*Genomics*
(...)

*Datamining*
(...)
