# Using-Genomics-to-Predict-and-Prevent-Cisplatin-Induced-Otoxicity
MSc Thesis source code. Completed under the supervision of Dr. Drögemöller at the University of Manitoba.
Both Linux and RStudio are used in scripts.

## This project is split into **two** parts:
# 1) Predicting cisplatin-induced ototoxicity through the development of a polygenic score(PGS)   
* 01_Harmonization_PGS -> Harmonizing input summary statistics 
* 02_develop_PGS -> Preparing files for SBayesR, running SBayesR and annotating output with VEP
* 03_Refine_PGS -> Gene-based refinement for cisplatin-induced ototoxicity (i.e. increase relevance to hearing and cisplatin cytotoxicity)
* 04_Testing_PGS-> Testing the performance of the cisplatin-induced ototoxicity PGS against a pediatric cisplatin-induced ototoxicity cohort using ReACt

# 2) Preventing cisplatin-induced ototoxicity by discovering potential otoprotectants through a transcriptome-wide association study (TWAS)
* 01_Harmonization_TWAS -> Harmonizing input summary statistics
* 02_SPrediXcan_TWAS -> Performing S-PrediXcan steps (i.e. imputation, post processing, tissue specific processing) as well as S-MultiXcan (aggregated tissue processing)
* 03_refine_and_finemap_TWAS -> Fine-mapping S-MultiXcan results as well as increasing relevance of genes to cisplatin-induced ototoxicity
* 04_drugrepurposing_TWAS -> Formatting filtered genesets for drug repurposing analyses in the Connectivity Map and also creating a figure to display output results

## Any questions or comments are welcome!
