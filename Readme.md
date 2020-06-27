# Pebble drift past the CO ice line in protoplanetary discs 
### Course project for *Reproducible and Interactive Data Analysis using Jupyter Notebooks* VT20

This Notebook reproduces (preliminary) results of the manuscript in preparation "Pebble drift past the CO ice line in protoplanetary discs", K. Ros & A. Johansen, to be submitted to *Astronomy & Astrophysics*.

## Instructions for running the notebook

1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)/[Anaconda](https://docs.anaconda.com/anaconda/install/).

2. Download the files from this GitHub repository

3. In the terminal, navigate to the folder you downloaded from GitHub

4. Create the environment
    - The file katrin_environment.yml in this folder contains the required packages.
    - To use this environment type the following into your terminal
	```
	conda env create -f katrin_environment.yml
	```
5. Now activate the environment by typing 
	```
	conda activate katrin_environment
	```
6. Run the notebook by typing
	```
	jupyter notebook
	```


## Extra useful features

Since the code I am working with gives output as an IDL .sav file, I found io.readsav from the scipy library very useful, as it allows me to import this data for use in python. 


## Responses to reviews


### Response to review 1

Dear Kedir,

Thank you very much for taking the time to review my project. I have now updated it according to your suggestions, I specify the updates below:

- Abstract: I have updated the abstract to read less like a summary, and I instead moved the scientific summary to after the abstract.

- Input/output: I am now using panda DataFrames to save the manipulated data, and to export the data to disc. For input I still use scipy as my input data is from IDL and I have not found a way to import this type of data using pandas.

- DOI: I have now added a DOI for my project.

Thanks again for your review,  
Katrin


### Response to review 2

Dear Saeid,

Thank you very much for taking the time to review my project. I have now updated it according to your suggestions, I specify the updates below:

- Input/output: I am now using panda DataFrames to save the manipulated data, and to export the data to disc. For input I still use scipy as my input data is from IDL and I have not found a way to import this type of data using pandas.

- DOI: I have now added a DOI for my project.

Thanks again for your review,  
Katrin


### Questions/contact
For any questions, please email katrin.ros@astro.lu.se


[![DOI](https://zenodo.org/badge/246933560.svg)](https://zenodo.org/badge/latestdoi/246933560)
