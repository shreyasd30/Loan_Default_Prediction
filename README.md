# Objective and Context

** Aegis Bank Inc. is a global financial institution with an extensive customer base spanning across the globe. Committed to providing excellent financial services, the bank places a strong emphasis on risk management and customer satisfaction. Recognizing the importance of ensuring the financial stability of its clients, Aegis Bank invests significant resources in predictive analytics to proactively identify potential risks.

As a recently onboarded Data Scientist in the Risk Management Department, my primary responsibility is to leverage data-driven insights to predict whether customers are at risk of defaulting on their loans. Aegis Bank aims to optimize its risk mitigation strategies by identifying patterns and characteristics associated with customers who might face challenges in meeting their financial obligations.

By employing advanced machine learning models and predictive analytics, I will analyze historical customer data to identify key features and trends that correlate with loan defaults. The goal is to develop a robust predictive model that can accurately forecast the likelihood of a customer defaulting on a loan. This proactive approach will empower Aegis Bank to tailor its risk management strategies, allowing for targeted interventions and support to customers who may be at risk.

Ultimately, the insights derived from this predictive modeling initiative will enable Aegis Bank to optimize resource allocation, enhance customer engagement, and maintain a robust risk management framework that aligns with the bank's commitment to delivering exceptional financial services globally. **

## Objective:

** To identify the different factors which leads to Defaultation of Loan repayments
To make a model to predict wheather a customer will default on his/her loan or not **

## Dataset:

The data contains customer loan type, their income and loan default status.

**ID** - Customer identifier (Unique in nature)

**Year** - Year in which the loan is taken

**Loan_Limit** - Two types of loan limits - CF and NCF CF - Conforming loan (Limit < 500,000) NCF - Non-conforming loan (No Limit, i.e. Limit > 500,000)

**Gender** - Customer's Gender

**Approve_in_adv** - Is customer pre-approved for the loan or not.

**Loan_type **- Type of loan (Type 1, Type 2 or Type 3)

**Loan_Purpose**- Purpose of loan (i.e. Loan taken for exactly what purpose - P1, P2, P3, P4)

**Credit_worthiness** - Credit worthiness type (L1 or L2)

**open_credit** - Open credit ype or not

**business_or_commercial** - Is the loan for business/commercial or not

**loan_amount** - Total loan amount taken from the bank

**Interest_rate_spread** - Interest rate charged by the banks to private sector customers minus the rate paid by commercial banks for demand, time, savings.

**Upfront_charges** - Upfront charges paid by customers

**term** - period for which the loan is taken

**Neg_ammortization** - The loan amount will go up even after paying because the amount owed by customer is not enough to cover the interest.

**interest_only** - Only interest paid by customer or not

**lump_sum_payment** - Did customer paid the lump sum amount or not

**property_value** - Current Total value of the property for which the loan is taken

**Construction_type** - Is the construction_type mh or sb (i.e. manufactured house or a small business)

**occupancy_type** - What is the occupancy type? (Primary residence, Secondary residence, or investment residence)

**Secured_by** - Loan secured by a home or a land.

**Total_unit** - Total aailable units of the home.

**Income** - Income of the customer

**Credity_type** - Credit type of customer (Experian, Equifax, CIB, CRIF)

**Credit_score** - Credit score of the customer

**co_applicant_credit_type** - Co-applicant credit card type

**Age** - Age of the customer

**submission_of_application** - Application submitted directly to the institution or nor.

**LTV** - Loan-to-Value Ratio used for assessment of lending financial risk that financial institutions examine before approving.

**Region** - Region of the bank

**Security_type** - Wheather the security type is direct or indirect

**Status** - Loan default status (i.e. 0 - Not defaulted, 1 - Defaulted on loan) dtir - Debt-to-income ratio assessed by banks before lending the money
