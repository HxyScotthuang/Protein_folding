# Protein_folding
This is the protein folding project for Oxford Summer project, under supervision of Dr.Cris Salvi. 
The works are done by Xingyue Huang and Ruotong Cao

There are 3 main objects we are trying to do:

1. Create a Neural-CDE model to predict protein-folding. 
     The details are written in cde-protein-prediction.ipynb, and the relavent features generation are shown in Feature_generation/generate_feature.ipynb
(Unfinished)

2. Attempt to train a signature inverse model that takes in a signature and return the reconstruction of the path.
     The details are in Signature inverse network.ipynb. The baseline methods are in Signatory-inverse-basic-property.ipynb
     
3. Re-create the pipeline of Alphafold1 for Casp13, for pytorch version, based on https://github.com/Urinx/alphafold_pytorch and https://github.com/leklab/alphafoldv1
     The details are in MyAlphafold1.ipynb

Note: All the ipynb files works only on Google Colab, so it would be the best if it can be recreated on Colab. The path directory are inside each of the ipynb files, so be sure to re-set all of these before actually running.

For further reference on how to re-create alphafold1 pipeline, check out the README file for https://github.com/Urinx/alphafold_pytorch: ReadMe for alphafold pytorch.md
