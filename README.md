# Welcome!
This repository consists of a simple script with Python code to reproduce MLR-QSPR models presented in the publication:

"Environmental impact of PFAS: Filling data gaps using theoretical quantum chemistry and QSPR modeling" by Michalina Mudlaff, Anita Sosnowska, Leonid Gorb, Natalia Bulawska and Tomasz Puzyn

Contents:
1) logP.xlsx - contains sheet with data necessary to reproduce the models
2) norman_pred.xlsx - contains a sheet with the descriptor values needed to predict n-octanol/water values from the Norman database
3) MLR.ipynb - simple Jupyter notebook script with Python code to reproduce the models, the script loads provided data from the xlsx file, fits models, performs predictions for the training, validation sets and predictions for compounds from Norman Database System. These generated results are sufficient to reproduce any plot, graph and remaining statistics presented in the publication.
4) LICENSE - self explanatory
5) requirements.txt - lists all libraries and their versions that were used to develop QSAR models
