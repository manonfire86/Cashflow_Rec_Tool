# Cashflow_Rec_Tool
This tool reconciles my cashflow transaction report with my receiving bank account and constructs a historical rec for the last month. Using regular expressions and the intersection()
function in pandas I map all received cashflows to the transaction data. Any missing rows are indication of cashflow breaks that require action to the servicer.
The tool then constructs a 30 day waterfall analysis of the cashflows to show all funds received and their adjustments.
