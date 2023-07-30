The **InsureViz** dashboard was built using publicly available data from the French government and the CASDataset R package about insurance claims.

**Car Insurance Datasets:**

1. **Claim Frequency Dataset:**
   - Contains 678,013 rows with one row per policyholder.
   - Provides information on the policyholders, their cars, and the number of claims they have made during the specified period.

2. **Claim Severity Dataset:**
   - Comprises 26,639 rows with an "id" column that is linked to the claim frequency dataset.
   - Includes a "claim amount" column that sums the total claim amount made by each policyholder for the specified period.

These two datasets are joined based on the "id" column to associate the claim amount with claims when there have been any.

**Geographic Datasets:**

1. **Regions Correspondance Dataset:**
   - Used to match old French regions (before 2016) with the current regions.

2. **Regions Polygons Dataset:**
   - Contains polygons for each of the new regions.

The combination of these datasets enables **InsureViz** to provide valuable insights into insurance claims, visualizing claim frequency, severity, and geographic patterns to facilitate data-driven decisions in the insurance domain.
