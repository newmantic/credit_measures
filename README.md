# credit_measures


Probability of Default (PD)
PD estimates the likelihood that a borrower will default on a loan within a given time frame.
PD = 1 / (1 + exp(-a * (Credit_Score - b)))
where a and b are constants typically based on historical data.

Loss Given Default (LGD)
LGD estimates the percentage of exposure that will be lost if a borrower defaults.
LGD = 1 - Recovery_Rate

Exposure at Default (EAD)
EAD estimates the total value exposed to loss at the time of default.
EAD = Current_Balance + (Credit_Limit - Current_Balance) * Utilization_Rate

Credit Value at Risk (Credit VaR)
Credit VaR estimates the maximum potential loss due to credit risk over a specific period, at a given confidence level.
Credit_VaR = EAD * LGD * (PD + Z * sqrt(PD * (1 - PD)))
where Z is the Z-score corresponding to the confidence level.

Expected Loss (EL)
EL calculates the expected loss due to credit risk, combining the probability of default, loss given default, and exposure at default.
EL = EAD * PD * LGD

Credit Spread
Credit Spread measures the difference in yield between a credit-risky bond and a risk-free bond.
Credit_Spread = Bond_Yield - Risk_Free_Rate

Debt-to-Income Ratio (DTI)
DTI measures the percentage of a borrower's income that goes towards debt payments.
DTI = Monthly_Debt_Payments / Monthly_Income

Interest Coverage Ratio (ICR)
ICR measures a company's ability to meet its interest payments with its earnings before interest and taxes (EBIT).
ICR = EBIT / Interest_Expense

Loan-to-Value Ratio (LTV)
LTV measures the ratio of a loan to the value of the asset purchased with the loan.
LTV = Loan_Amount / Asset_Value

Debt Service Coverage Ratio (DSCR)
DSCR measures a company's ability to service its debt with its net operating income.
DSCR = Net_Operating_Income / Total_Debt_Service

Z-Score
The Z-Score is a credit scoring model that estimates the likelihood of bankruptcy.
Z = 1.2 * (Working_Capital / Total_Assets) + 1.4 * (Retained_Earnings / Total_Assets) + 3.3 * (EBIT / Total_Assets) + 0.6 * (Market_Value_Equity / Total_Liabilities) + 1.0 * (Sales / Total_Assets)

FICO Score
Explanation: The FICO score is a credit score that estimates the creditworthiness of a borrower.
FICO_Score = 850 * (0.35 * Payment_History + 0.30 * Amounts_Owed + 0.15 * Length_of_Credit_History + 0.10 * New_Credit + 0.10 * Credit_Mix)

Altman Z-Score
The Altman Z-Score is a measure used to predict the probability of a company going bankrupt within two years.
Altman_Z = 1.2 * (Working_Capital / Total_Assets) + 1.4 * (Retained_Earnings / Total_Assets) + 3.3 * (EBIT / Total_Assets) + 0.6 * (Market_Value_Equity / Total_Liabilities) + 1.0 * (Sales / Total_Assets)

Interest Rate Spread
Interest Rate Spread is the difference between the interest rate on loans and the interest rate on deposits.
Interest_Rate_Spread = Loan_Rate - Deposit_Rate

Capital Adequacy Ratio (CAR)
CAR measures a bank's capital in relation to its risk-weighted assets.
CAR = (Tier1_Capital + Tier2_Capital) / Risk_Weighted_Assets

Credit Utilization Ratio
Credit Utilization Ratio measures the amount of credit used compared to the total credit available.
Credit_Utilization_Ratio = Credit_Used / Credit_Limit

Debt Yield
Debt Yield measures the return a lender can expect from a loan, based on earnings before interest and taxes (EBIT).
Debt_Yield = EBIT / Loan_Amount

Debt-to-Equity Ratio (D/E)
D/E measures a company's financial leverage by dividing its total liabilities by shareholder equity.
D/E = Total_Liabilities / Shareholder_Equity

Covenant Lite Loans Percentage
Measures the percentage of loans that have fewer covenants, which typically indicates higher risk.
Covenant_Lite_Percentage = Covenant_Lite_Loans / Total_Loans

Current Ratio
Current Ratio measures a company's ability to pay short-term obligations with its short-term assets.
Current_Ratio = Current_Assets / Current_Liabilities

Quick Ratio
Quick Ratio is similar to the Current Ratio but excludes inventory, offering a stricter measure of liquidity.
Quick_Ratio = (Current_Assets - Inventory) / Current_Liabilities

Cash Ratio
Cash Ratio measures a company's ability to pay off its short-term liabilities with cash and cash equivalents only.
Cash_Ratio = Cash / Current_Liabilities

Operating Cash Flow to Debt Ratio
Operating Cash Flow to Debt Ratio measures how well a company's cash flow from operations can cover its total debt.
Operating_Cash_Flow_to_Debt = Operating_Cash_Flow / Total_Debt

Free Cash Flow Yield
Free Cash Flow Yield compares free cash flow to market value, indicating how much cash a company generates relative to its size.
Free_Cash_Flow_Yield = Free_Cash_Flow / Market_Value_of_Equity

Net Debt to EBITDA
Net Debt to EBITDA indicates how many years it would take to pay off debt with EBITDA (earnings before interest, taxes, depreciation, and amortization).
Net_Debt_to_EBITDA = (Total_Debt - Cash) / EBITDA

Debt-to-Asset Ratio
Debt-to-Asset Ratio measures the percentage of a company's assets that are financed by debt.
Debt_to_Asset = Total_Debt / Total_Assets

Fixed Charge Coverage Ratio (FCCR)
FCCR measures a firm's ability to cover fixed charges, such as leases and debt payments.
FCCR = (EBIT + Fixed_Charges) / Fixed_Charges

Asset Coverage Ratio
Asset Coverage Ratio compares a company's assets (minus intangibles) to its liabilities, indicating how well the assets cover the liabilities.
Asset_Coverage = (Total_Assets - Intangible_Assets) / Total_Liabilities

Gross Debt Service Ratio (GDSR)
GDSR measures the percentage of gross income that goes towards mortgage payments and property taxes.
GDSR = (Mortgage_Payments + Property_Taxes) / Gross_Income

Total Debt Service Ratio (TDSR)
TDSR measures the percentage of gross income required to cover all debt payments.
TDSR = Total_Debt_Payments / Gross_Income

Interest Burden Ratio
Interest Burden Ratio measures the proportion of EBIT that remains after paying interest expenses.
Interest_Burden = EBIT / (EBIT + Interest_Expense)

Return on Capital Employed (ROCE)
ROCE measures the efficiency and profitability of a company's capital investments.
ROCE = EBIT / Capital_Employed
where Capital_Employed = Total_Assets - Current_Liabilities.

Altman Z-Prime Score (Z')
A variation of the Altman Z-Score, tailored for private firms, estimating the likelihood of bankruptcy.
Z'_Score = 0.717 * (Working_Capital / Total_Assets) + 0.847 * (Retained_Earnings / Total_Assets) + 3.107 * (EBIT / Total_Assets) + 0.420 * (Book_Value_of_Equity / Total_Liabilities) + 0.998 * (Sales / Total_Assets)

Debt Repayment Ratio
Explanation: Measures the proportion of income used to repay debt.
Debt_Repayment_Ratio = Annual_Debt_Payments / Annual_Income

Interest Coverage Ratio (Earnings-Based)
An alternative to the traditional Interest Coverage Ratio, using net income instead of EBIT.
ICR_Earnings_Based = Net_Income / Interest_Expense

Debt-to-Capital Ratio
Measures the proportion of a company’s capital that is provided by debt.
Debt_to_Capital = Total_Debt / (Total_Debt + Total_Equity)

Operating Margin
Measures the percentage of revenue left after paying for variable costs of production.
Operating_Margin = EBIT / Revenue

Cash Flow to Debt Ratio
Measures how well a company's cash flow can cover its total debt.
Cash_Flow_to_Debt = Cash_Flow_from_Operations / Total_Debt

Leverage Ratio
Measures the proportion of a company's capital structure that is financed by debt.
Leverage_Ratio = Total_Assets / Total_Equity

Dividend Coverage Ratio
Measures a company’s ability to pay its dividends from earnings.
Dividend_Coverage_Ratio = Net_Income / Dividends_Paid

Loan Loss Provision Ratio
Measures the percentage of loans that a bank has set aside as a provision for loan losses.
Loan_Loss_Provision_Ratio = Loan_Loss_Provisions / Total_Loans

Reserves to Loans Ratio
Measures the percentage of reserves that a bank holds relative to its total loans.
Reserves_to_Loans_Ratio = Reserves / Total_Loans

Non-Performing Loan Ratio
Measures the proportion of loans that are in default or close to being in default.
Non_Performing_Loan_Ratio = Non_Performing_Loans / Total_Loans

Cost of Debt
Measures the effective rate that a company pays on its debt.
Cost_of_Debt = Interest_Expense / Total_Debt

Days Sales Outstanding (DSO)
Measures the average number of days that it takes a company to collect payment after a sale has been made.
DSO = (Accounts_Receivable / Total_Credit_Sales) * Days

Days Payable Outstanding (DPO)
Measures the average number of days that a company takes to pay its suppliers.
DPO = (Accounts_Payable / Cost_of_Goods_Sold) * Days

Days Inventory Outstanding (DIO)
Measures the average number of days that inventory is held before it is sold.
DIO = (Inventory / Cost_of_Goods_Sold) * Days

Current Liabilities to Net Worth Ratio
Measures the proportion of current liabilities to shareholders' equity.
Current_Liabilities_to_Net_Worth = Current_Liabilities / Net_Worth

Net Profit Margin
Measures how much of each dollar in revenue a company actually keeps in earnings.
Net_Profit_Margin = Net_Income / Revenue

Cash Conversion Cycle (CCC)
Measures the time it takes for a company to convert its investments in inventory and other resources into cash flows from sales.
CCC = DSO + DIO - DPO

