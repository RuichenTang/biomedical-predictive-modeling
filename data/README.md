# Data

## Included: Wisconsin Diagnostic Breast Cancer

`breast_cancer_wisconsin.csv` contains 569 observations, a binary diagnosis label, and 30 real-valued predictors derived from digitized images of breast-mass cell nuclei.

Source: Wolberg, W., Mangasarian, O., Street, N., & Street, W. (1993). *Breast Cancer Wisconsin (Diagnostic)*. UCI Machine Learning Repository. [https://doi.org/10.24432/C5DW2B](https://doi.org/10.24432/C5DW2B).

License: CC BY 4.0. The file is redistributed here with attribution.

## Download separately: METABRIC

The METABRIC combined file is not committed to keep the repository lightweight and make its provenance explicit.

1. Open the Kaggle dataset [Breast Cancer Gene Expression Profiles (METABRIC)](https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric).
2. Download `METABRIC_RNA_Mutation.csv` (approximately 8.39 MB).
3. Place it at:

   ```text
   data/METABRIC_RNA_Mutation.csv
   ```

The expected file has 1,904 rows and 693 columns. The Kaggle page lists the database under the Open Database License and the contents under the Database Contents License; consult the source page for the controlling terms.

## Downloaded automatically: prostate data

`analysis/01_prostate_stepwise.Rmd` reads the prostate example directly from the data archive accompanying *The Elements of Statistical Learning*:

```text
https://hastie.su.domains/ElemStatLearn/datasets/prostate.data
```

