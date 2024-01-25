#Welcome!
This repository consists of a simple script with Python code to reproduce MLR-QSAR models presented in the publication:

"Environmental impact of PFAS: Filling data gaps using theoretical quantum chemistry and QSPR modeling" by Michalina Mudlaff, Anita Sosnowska, Leonid Gorb, Natalia Bulawska and Tomasz Puzyn

Contents:

logP.xlsx - contains sheet with data necessary to reproduce the models
norman_pred.xlsx - contains a sheet with the descriptor values needed to predict n-octanol/water values from the Norman database
MLR.ipynb - simple Jupyter notebook script with Python code to reproduce the models, the script loads provided data from the xlsx file, fits models, performs predictions for the training, validation sets and predictions for compounds from Norman Database System. These generated results are sufficient to reproduce any plot, graph and remaining statistics presented in the publication.
LICENSE - self explanatory
requirements.txt - lists all libraries and their versions that were used to develop QSAR models
