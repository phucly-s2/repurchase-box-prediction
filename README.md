# repurchase-box-prediction

Extrapolation Methodology:
1. Start with the activation rate, we will calculate the marginal activation rate (how many % of activated customers month n will be activated in month n+1) (n>1)
2. We assume the future marginal activation by taking a moving average of the previous N rows (N=3)
3. Here we extrapolate Cohort Activation rate by multiple (n)th columns in marginal activation rate by (n-1)th column.
