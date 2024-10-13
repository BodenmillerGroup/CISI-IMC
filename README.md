# CISI-IMC
Scripts for CISI-IMC publication

## analysis
ipynb files to perform analyses demonstrated in the manuscript. First line of each file indicates which figure it corresponds to.

## code
python files contaning functions used in the codes in "analysis" folder. 
- simulate_A: Simulating the decompression performance of barcoding matrix.
- smaf: Calculating dictionary from single cell expresssion data.
- utils: other functions

## demo
Demo ipynb script to go through CISI-IMC workflow with a subset of our datasets. Simply run Demo_cisi_imc.ipynb. Data needed to run the demo script is stored in demo/data/ folder.

## env
yml file to create a python environment for CISI-IMC.
This may take a few minutes.
```sh
conda env create -f env/cisi_imc_env.yml
conda activate cisi_imc_env
```

## report
Rmd files to produce the plots in the manuscript.

