# NOTA: The Choice of Mugwumps?

## Description and Background: 
This project explores how NOTA votes in India impact the vote share of independent candidates. This repository consists of the following files:

1. NOTA_Mugwumps.pdf : Contains introduction, literature review, methodology, results, conclusion and appendices. This document is the torso of the project. Interested reader should start here. A skimming reader should also start here but can skip literature review, methodology, and the appendices.     

2. doc_codes.ipynb : Documents codes used to produce figures and tables used in NOTA_Mugwumps.pdf. This file is for the meticulous reader who wants to verify the project results for him/herself. All codes are written in Python3.

3. ancillary_files (directory) : Broadly, these are data files used in doc_codes.ipynb. In particular, it contains:
   * 3.1. cleanest_data.csv : Main input file containing pre_processed data used in doc_codes.ipynb

   * 3.2. pre_processing_data_meta.txt : Details about data source and initial data cleaning

   * 3.3. LokDhabaCodebook.pdf : Description of variables in the extracted, full dataset

   * 3.4. variables_description : Description of variables used and feature engineered in the dataset

   * 3.5. census_codes.csv : Contains census codes for various states used in assigning unique code to constituencies

   * 3.6. analysis_df.csv, input_top_3_new.csv, pivot_n_nota_format.csv, pivot_nonulls.csv : Files used as data input in doc_codes.ipynb. All of these files are derived from cleanest_data.csv using Python but due to trivial issues(ones that I mention in ipynb file), I had to export them into excel, correct header row and then input these files back into the ipynb file.

