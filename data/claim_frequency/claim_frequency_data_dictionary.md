# Data Dictionary for "claim_frequency.csv"

The "claim_frequency.csv" file contains information about insurance policies and their related claims. Here is a description of the variables present in the dataset:

1. **IDpol:** The IDpol is a unique identifier assigned to each insurance policy. It is used to link this dataset with the claim severity dataset, enabling the association of claims with their corresponding severity.

2. **ClaimNb:** ClaimNb represents the number of claims made during the exposure period for a particular policy. It indicates how many claims were reported for a given policy within the specified time frame.

3. **Exposure:** Exposure denotes the period of exposure for a policy, measured in years. It represents the duration for which the policyholder was covered under the insurance policy.

4. **VehPower:** VehPower represents the power of the insured car and is categorized as an ordered categorical variable. This variable helps classify cars based on their engine power into specific groups or ranges.

5. **VehAge:** VehAge refers to the age of the insured vehicle in years at the time of observation. It provides insights into the age distribution of the insured cars in the dataset.

6. **DrivAge:** DrivAge indicates the age of the driver associated with the policy. In France, individuals are legally allowed to drive a car at the age of 18. This variable provides information about the age distribution of the policyholders in the dataset.

7. **BonusMalus:** Bonus/malus, between 50 and 350: <100 means bonus, >100 means malus in France.

8. **VehBrand:** VehBrand indicates the car brand (unknown categories).The car brand is divided into the following groups:
  - A: Renaut, Nissan, and Citroen
  - B: Volkswagen, Audi, Skoda, and Seat
  - C: Opel, General Motors, and Ford
  - D: Fiat
  - E: Mercedes, Chrysler, and BMW
  - F: Japanese (except Nissan) and Korean
  - G: Other

9. **VehGas:** VehGas indicates the car gas, Diesel or regular.

10. **Area:** Area indicates the age of the density value of the city community where the car driver lives in: from "A" for rural area to "F" for urban centre.

11. **Density:** Density indicates the density of inhabitants (number of inhabitants per km2) in the city the driver of the car lives in.

12. **Region:** Region indicates the policy region in France (based on the 1970-2015 classification).

This data dictionary serves as a reference guide, providing a clear understanding of the variables and their meanings in the "claim_frequency.csv" dataset. It is intended to help users interpret and analyze the data effectively, facilitating data-driven insights and decision-making processes.
