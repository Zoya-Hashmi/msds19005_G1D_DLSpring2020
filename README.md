# G1D_DLSpring2020
“This repository contains code and results for the Course Project by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This repository is only for learning purposes and is not intended to be used for commercial purposes.”

## Abstract
In the wake of the current pandemic of COVID19 it is ever more important to speed up the reliable drug discovery process. Deep learning has been introduced into the field of Cheminformatics to predict the Binding Affinities from pairs of drugs and target proteins. The drugs and proteins can both be represented as text sequences, graphs and 3D structures. Additionally, meaningful molecular images that hold atomic and bonding information of the molecule are also viable representations. Images of Proteins however don’t hold any meaningful information. Image, Graph, 3D and Text based representations for molecular inputs have been considered for the task of DTA, but proteins have mostly been used as character sequences or expensive 3D crystal structure is used, which is not suitable for the prompt and low budget prediction task. The DGraphDTA baseline that we followed uses the protein sequence information to estimate the contact maps for proteins which can be used to generate protein graphs. In our project, we explore the limitations of their method, and perform a series of experiments with the aim to improve upon their results. Finally, we predict the binding affinities for COVID Protienase 3CL-PRO with the drugs from baseline Davis dataset, using our experimental models. The contact map for the COVID Proteinase was estimated from the MapPred webserver.

## Experiment (DGraphDTA) results produced on Davis testset
|Experiments | CI(std) | MSE(std) | Pearson(std)|
| :---: | :---: | :---: | :---: |
|reported | 0.89 | 0.21 | 0.85|
|Reproduced | 0.89 | 0.23 | 0.84|
|CNN(100x100) | 0.76 | 0.58 | 0.55|
|CNN(200x200) | 0.88 | 0.25 | 0.83|
|no aug.(100x100) | 0.88 | 0.23 | 0.84|
|Ensemble no aug. | 0.88 | 0.23 | 0.83|
|Dropout | 0.88 | 0.23 | 0.84|


## Disclaimer
This work is based on two papers on Drug Target Affinity Prediction. 
* Mingjian Jiang, Zhen Li, Shugang Zhang, Shuang Wang, Xi-aofeng Wang,  Qing Yuan,  and Zhiqiang Wei.   Drug–targetaffinity  prediction  using  graph  neural  network  and  contactmaps.RSC Advances, 10(35):20701–20712, 2020.
* Ahmet  Sureyya  Rifaioglu,   Esra  Nalbat,   Volkan  Atalay,Maria   Jesus   Martin,   Rengul   Cetin-Atalay,   and   TuncaDo ̆gan.   Deepscreen:  high  performance  drug–target  inter-action prediction with convolutional neural networks using2-d structural compound representations.Chemical Science,11(9):2531–2557, 2020.

### Links
**Website** https://sites.google.com/itu.edu.pk/drug-discovery-with-dl/home \ <br>

**Paper** https://drive.google.com/file/d/1hqKu48gq1vtArtOXAWzqd_Brt0PwQroh/view <br>
