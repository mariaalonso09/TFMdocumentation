In this repository you will find:

1. Supplementary material folder where there are 2 more folders, one of them (SNPS_Filtered_Annotation) contains the final SNPS obtained in the filtering and the biological consequences of these SNPs.
The second folder (Survival Analysis) contains the graphs obtained in the survival analysis of the FRY gene as well as all the breast cancer subtypes in the "subtypes" folder.

2. Survival analysis: Code used to perform the survival analysis following the following steps:

Data loading and libraries: Expression data of the FRY gene and clinical data are loaded.
Preprocessing: Clinical and expression data are adjusted to combine both sets.
Cox models: The effects of FRY gene expression on overall survival (OS) and disease-free progression (FFP) are analyzed.
Categories and graphs: The data are categorized into high and low expression groups and the survival curves are graphed.
Subtype analysis: Analysis for specific breast cancer subtypes is performed using the PAM50 classification and results are compared by expression tertiles of the FRY gene.

3. Annotation ensembl This R code performs the following steps: Configures biomaRt to access SNP data from Ensembl.

Reads genetic variant data from different files.
Combines the data into a single data frame.
Obtains additional information about the variants using biomaRt.
Merges the additional information with the original data.
Exports the combined data frame to an Excel file.

4. Manhhatn plot This R code performs the following steps: Setup: Prepares the environment to display the code in the output.

Loading libraries: Imports readr, dplyr, and plotly.
Reading data: Reads data files for BRCA1 and BRCA2.
Filtering: Selects data in a range of specific positions.
Chart Creation: Generates "Manhattan Plot" type charts for BRCA1 and BRCA2 and displays them on a vertical subplot.
