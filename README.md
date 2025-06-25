| Column                     | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| ID                         | Client loan application ID                                                  |
| year                       | Year of loan application                                                    |
| loan_limit                 | Indicates if the loan is conforming (cf) or non-conforming (ncf)           |
| Gender                     | Gender of the applicant (male, female, joint, sex not available)           |
| approv_in_adv              | Whether the loan was approved in advance (pre, nopre)                      |
| loan_type                  | Type of loan (type1, type2, type3)                                         |
| loan_purpose               | Purpose of the loan (p1, p2, p3, p4)                                       |
| Credit_Worthiness         | Credit worthiness category (l1, l2)                                        |
| open_credit                | Whether the applicant has open credit accounts (opc, nopc)                 |
| business_or_commercial     | If the loan is for business/commercial use (ob/c) or personal (nob/c)      |
| loan_amount                | Amount of money borrowed                                                   |
| rate_of_interest           | Interest rate charged on the loan                                          |
| Interest_rate_spread       | Difference between loan interest and benchmark rate                        |
| Upfront_charges            | Initial charges for securing the loan                                      |
| term                       | Duration of the loan in months                                             |
| Neg_ammortization          | Whether loan allows negative amortization (neg_amm, not_neg)              |
| interest_only              | If the loan is interest-only (int_only, not_int)                           |
| lump_sum_payment           | Whether a lump sum is required at end (lpsm, not_lpsm)                     |
| property_value             | Value of the property financed                                             |
| construction_type          | Type of construction (sb - site built, mh - manufactured home)            |
| occupancy_type             | Occupancy type (pr, sr, ir)                                                |
| Secured_by                 | Type of collateral securing the loan (home, land)                          |
| total_units                | Number of units in the property (1U, 2U, 3U, 4U)                            |
| income                     | Applicant’s annual income                                                  |
| credit_type                | Applicant’s credit source (CIB, CRIF, EXP, EQUI)                           |
| Credit_Score               | Applicant’s credit score                                                   |
| co-applicant_credit_type   | Co-applicant’s credit type (CIB, EXP, etc.)                                |
| age                        | Applicant’s age                                                            |
| submission_of_application  | How the application was submitted (to_inst, not_inst)                      |
| LTV                        | Loan-to-Value ratio                                                        |
| Region                     | Geographic region (North, south, central, North-East)                      |
| Security_Type              | Type of loan security (direct, indirect)                                   |
| Status                     | Target variable: 1 = defaulted, 0 = not defaulted                          |
| dtir1                      | Debt-to-Income ratio                                                       |
