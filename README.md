This report documents the development and validation of a deterministic term life insurance pricing model implemented in R.
The purpose of the project was to develop a reusable actuarial pricing framework capable of projecting policy-level mortality, 
lapse behaviour, expected claims, expenses and present values of future cash flows to calculate indicated annual premiums.
The model was applied to a synthetic portfolio containing 100,000 individual term life insurance policies.
Validation activities included testing the relationship between premiums and policyholder characteristics; evaluating changes in mortality, 
lapse, interest rates, expenses and profit margins; reconciling expected death calculations; checking portfolio record integrity and premium calculations; 
and investigating premium distributions and high-premium observations.
All 14 manually recorded directional and reconciliation tests passed. Seven automated portfolio integrity checks also passed, as did the separate cash-flow 
reconciliation check.
The results demonstrate that the model behaves consistently with its programmed assumptions. However, the model uses synthetic data and illustrative 
assumptions and has not been validated against actual insurer experience or commercial pricing benchmarks.
