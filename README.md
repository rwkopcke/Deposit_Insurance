# Deposit Insurance
Excel VBA workbook that models a DI fund's net assets using Monte Carlo simulations, using data for each bank, policy paramenters, distributions for
macro variables, each bank's probability of failing, and distributions of recovery rates to project the distribution of the DI fund's net balances for
10 years, reported by selected quantiles.
&npbs;

In Alternative I simulations, the user specifies which banks fail and the years in which they fail.
In Alternative II simulations, the Monte Carlo specifies which banks fail and the years in which they fail. 
&npbs;

The automatic failure version of the workbook draws a set of random bank failures in Alternative II simulations each time the model runs.
The manual failure version of the workbook draws a set of random bank failures in Alternative II simulations only when user chooses to do so.
This last version allows users to isolate the effects of changing policy parameters from the effects of changing the identities of the banks that fail and the timing of their failures.
The manual failure II version is “rescaled” to total deposits, rather than insured deposits.  The target ratio for the fund’s assets (the maximum ratio) is a proportion of total deposits. This version also contains minor alterations in the input sheets, the code, and the output sheets.
