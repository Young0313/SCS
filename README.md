# SCS
This is the official code and datsets for paper "SCS: Subgraph Contrastive Supervised Neural Network for Link Prediction".  
All code and datasets will be available after review.

# Enviroment
* python == 3.8.10
* pytorch == 1.12.0
* pytorch_geometric == 2.3.0
* networkx == 2.4.0
* scikit-learn == 1.2.1
* scipy == 1.10.0

# Usage
`python main.py --parameters`  
eg: for plain graphs  
`python main.py --data-name BUP --test-ratio 0.3`  
eg: for attributed graphs  
`python main.py --planetoid --data-name Cora --test-ratio 0.3`  
detail information about parameters can be found in arg_setting.py

# Reference
There are some useful code provided by following papers.
* Cai L, Li J, Wang J, et al. Line graph neural networks for link prediction[J]. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2021, 44(9): 5103-5113.
* https://github.com/LeiCaiwsu/LGLP

* Velickovic P, Fedus W, Hamilton W L, et al. Deep graph infomax[J]. ICLR (Poster), 2019, 2(3): 4.
* https://github.com/PetarV-/DGI  

Thanks for their great work!
