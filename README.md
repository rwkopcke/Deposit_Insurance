# Deposit_Insurance
Excel VBA workbook that models DIs net assets using Monte Carlo simulations.  The model uses data for each bank, policy paramenters, distributions for
macro variables, each bank's probability of failing, and distributions of recovery rates to project the distribution of the DI fund's net balances for
10 years, reported by selected quantiles.
In Alternative I simulations, the user to specify which banks fail and the years in which they fail.
In Alternative II simulations, the Monte Carlo specifies which banks fail and the years in which they fail. 
The automatic failure version of the .xlsxm draws a set of random bank failures in Alternative II simulations each time the model runs.
The manual failure version of the .xlsm draws a set of random bank failures in Alternative II simulations only when user chooses to do so.
