# Deposit Insurance
Excel VBA workbook that models a DI fund's net assets using Monte Carlo simulations, using data for each bank, policy paramenters, distributions for
macro variables, each bank's probability of failing, and distributions of recovery rates to project the distribution of the DI fund's net balances for
10 years, reported by selected quantiles.
In Alternative I simulations, the user specifies which banks fail and the years in which they fail.
In Alternative II simulations, the Monte Carlo specifies which banks fail and the years in which they fail. 
The automatic failure version of the workbook draws a set of random bank failures in Alternative II simulations each time the model runs.
The manual failure version of the workbook draws a set of random bank failures in Alternative II simulations only when user chooses to do so.
This last version allows users to isolate the effects of changing policy parameters from the effect of changing the identities of the banks that fail and the timing of their failures.
