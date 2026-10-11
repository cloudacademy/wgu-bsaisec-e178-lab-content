# Datasets

## creditcard_fraud_sample.csv.gz

A sample of the ULB **Credit Card Fraud Detection** dataset: card transactions made by European cardholders over two days in September 2013.

| Property | Value |
| --- | --- |
| Source | OpenML dataset 1597 (`creditcard`), <https://www.openml.org/d/1597> |
| Licence (OpenML) | Public |
| Rows | 24,473 (473 fraud, 1.93%) |
| Columns | `Time`, `V1`–`V28` (PCA components released by the bank to protect cardholder confidentiality), `Amount`, `Class` (1 = fraud) |

The sample keeps every unique fraud transaction and 24,000 randomly sampled legitimate ones, after removing 1,081 duplicate rows from the full 284,807-row dataset. Values are rounded to six decimal places.

### Citation

Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi. *Calibrating Probability with Undersampling for Unbalanced Classification.* IEEE Symposium Series on Computational Intelligence (SSCI), 2015.
