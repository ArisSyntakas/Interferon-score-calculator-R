# Interferon-score-calculator-R

Before creating the IFN count tables, all sample raw counts (both control & disease) should be normalized together, ideally with the TPM method but any other method will work if raw counts are not available. Then the combined normalized table should be split in two as seen below:

This script requires two dataframes:
1)A dataframe of disease interferon counts/transcripts with row names being the interferon genes and column names being the sample names, labeled "IFN_disease"
2)A dataframe of control interferon data with a similar structure as above labeled "IFN_controls"
