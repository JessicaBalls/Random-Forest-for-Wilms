# Random-Forest-for-Wilms
# Python code for the training of a Random Forest classifier for expression data for Wilms tumour samples (TaqMan Cards A and B)  
# Prior to training the Random forest, ct vlaues are normalised with ath-159a and Pycombat 
# Pycombat used to account for any batch affects between TaqMan cards: Wilms patients and 9 non-cancer controls, and GCT data and an additional 6 non-cancer controls 
# Low abundance markers are filtered out; defined as miRNAs with a mean ct value > 28 in WT samples 
# SHAP scores are calculated and the 100 top ranking miRNAs are exported 
Log2FC > 1 used as an additional filter 
