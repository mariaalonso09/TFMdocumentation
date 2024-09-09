In this repository you will find:

1. Supplementary material folder where there are 2 more folders, one of them (SNPS_Filtered_Annotation) contains the final SNPS obtained in the filtering and the biological consequences of these SNPs.
The second folder (Survival Analysis) contains the graphs obtained in the survival analysis of the FRY gene as well as all the breast cancer subtypes in the "subtypes" folder.

2. Survival analysis: Code used to perform the survival analysis following the following steps:

  2.1. Data loading and libraries: Expression data of the FRY gene and clinical data are loaded.
  2.2. Preprocessing: Clinical and expression data are adjusted to combine both sets.
  2.3. Cox models: The effects of FRY gene expression on overall survival (OS) and disease-free progression (FFP) are analyzed.
  2.4. Categories and graphs: The data are categorized into high and low expression groups and the survival curves are graphed.
  2.5. Subtype analysis: Analysis for specific breast cancer subtypes is performed using the PAM50 classification and results are compared by expression tertiles of the FRY gene.

3. Annotation ensembl This R code performs the following steps: Configures biomaRt to access SNP data from Ensembl.

  3.1. Reads genetic variant data from different files.
  3.2. Combines the data into a single data frame.
  3.3. Obtains additional information about the variants using biomaRt.
  3.4. Merges the additional information with the original data.
  3.5. Exports the combined data frame to an Excel file.

4. Manhhatn plot This R code performs the following steps: Setup: Prepares the environment to display the code in the output.

  4.1. Loading libraries: Imports readr, dplyr, and plotly.
  4.2. Reading data: Reads data files for BRCA1 and BRCA2.
  4.3. Filtering: Selects data in a range of specific positions.
  4.4. Chart Creation: Generates "Manhattan Plot" type charts for BRCA1 and BRCA2 and displays them on a vertical subplot.
