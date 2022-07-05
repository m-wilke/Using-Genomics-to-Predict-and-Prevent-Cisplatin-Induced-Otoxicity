# Using-Genomics-to-Predict-and-Prevent-Cisplatin-Induced-Otoxicity
MSc Thesis source code. Completed under the supervision of Dr. Drögemöller at the University of Manitoba.


This project is split into two parts:
#1) Predicting cisplatin-induced ototoxicity through the development of a polygenic score (PGS)   
01_Harmonization_PGS -> Harmonizing input summary statistics
02_develop_PGS -> Preparing files for SBayesR, running SBayesR and annotating output with VEP
03_refine_PGS -> 
04_testing_PGS-> 

#2) Preventing cisplatin-induced ototoxicity through discovering potential otoprotectants through a transcriptome-wide association study (TWAS)
01_Harmonization_TWAS -> Harmonizing input summary statistics
02_S-PrediXcan_TWAS -> Performing S-PrediXcan steps (i.e. imputation, post processing, tissue specific processing) as well as S-MultiXcan (aggregated tissue processing)
03_refine_and_finemap_TWAS -> Fine-mapping S-MultiXcan results as well as increasing relevance of genes to cisplatin-induced ototoxicity through various refinement strategies 
04_drugrepurpoinsg_TWAS -> Formatting filtered genesets for drug repurposing analyses in the Connectivity Map and also creating a figure to display output results

Both Linux and RStudio are used in scirpts and is indicated in the files.

#Any questions or comments are welcome!
