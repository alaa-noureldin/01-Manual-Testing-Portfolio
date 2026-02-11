Stream,Component,Req-ID,Test Case ID & Name,Actor,Objective (short),Test Data,Step,Action / Steps,Expected Result
Alerts,SMS,As-is,Alerts_LAA_Retail_PerformLoanDisbursement_EGP_ByMaker_A1,Maker,Validate that maker can perform loan disbursement for EGP loan account,Creation and Disbursement of Loan account for the Subscribed customer,"1- Created Loan A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Activation user Logged into the system
,,,,,,,,2,Navigate to PLD Screen
,,,,,,,,3,"Navigate to ""Disbursement Details"" Tab"
,,,,,,,,4,"1-Fill in Mandatory fields
A/c. ID
Transaction Type: Transfer
Value Date
Disbursement Amt
2-Click Continue"
,,,,,,,,5,Navigate to Loan Fees Details
,,,,,,,,6,Fill in Mandatory fields
,,,,,,,,7,"Click on ""Submit"" Button"
Alerts,SMS,As-is,Alerts_LAA_Retail_Verify_LoanDisbursement_EGP_ByChecker_A2,Checker,Validate that checker can verify on perform loan disbursement for EGP loan account,Creation and Disbursement of Loan account for the Subscribed customer,"1- Created Loan A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Activation user Logged into the system
,,,,,,,,2,Navigate to VLDR Screen
,,,,,,,,3,Enter A/c. ID
,,,,,,,,4,"Click on ""Submit"" button"
Alerts,SMS,ASST_ALERT_02,Alerts_SMS_RetailCustomer_RealTime_LoanDisbursement_By User_A3,User,Validate that the customer receives SMS immediately after a Loan Disbursement,Creation and Disbursement of Loan account,"1- Created Loan A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Customer receives SMS after a loan disbursement
Alerts,SMS,ASST_0110,Alerts_ODA_Retail_ModifySanctionLimit_EGP_ByMaker_B1,Maker,Validate that maker can modify sanctioned limit for Retail OVD Acc,Modification of Overdraft Limit for the Subscribed customer,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Branch Maker user Logged into the system
,,,,,,,,2,"Navigate to ""Modify Sanction Limits / MSL"" Screen"
,,,,,,,,3,Enter A/c. ID
,,,,,,,,4,Click on Go button
,,,,,,,,5,"Click on ""Edit Icon"" in the record inside Sanction Limit Details Table"
,,,,,,,,6,"1- Modify the following Dropdown lists/fields:
2- Select for Edit: Yes
3- Sanction Limit"
,,,,,,,,7,Click on Update button
,,,,,,,,8,Click on Submit button
Alerts,SMS,ASST_0110,Alerts_ODA_Retail_Verify_ModifySanctionLimit_EGP_ByChecker_B2,Checker,Validate that checker can verify edited sanctioned limit for Retail OVD Acc,Modification of Overdraft Limit for the Subscribed customer,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Branch Checker user Logged into the system
,,,,,,,,2,"Navigate to ""Verify Sanction Limits / VSL"" Screen"
,,,,,,,,3,Enter A/c. ID
,,,,,,,,4,Click on Go button
,,,,,,,,5,Click on Update button
Alerts,SMS,ASST_ALERT_36,Alerts_SMS_RealTime_ModificationOfOverdraftLimit_ByUser_B3,User,Validate that the subscribed SMS customer receives SMS immediately after a Modification of Overdraft Limit,Modification of Overdraft Limit for the customer,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Validate that the customer receives SMS after a Modification of Overdraft Limit
Alerts,SMS,As-is,Alerts_ODA_Retail_OpenOverdraftAccount_Unsecured_85026_EGP_ByMaker_C1,Maker,"Validate that maker can create Un secured Overdraft Staff Account ""85026"" in EGP Currency",Creation of Overdraft Limit for the Subscribed customer,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Branch Maker user Logged into the system
,,,,,,,,2,"Navigate to ""Open Overdraft Account / OOA"" Screen"
,,,,,,,,3,"Navigate to ""Basic A/c. Details"" Tab"
,,,,,,,,4,"1-Fill in Mandatory fields
CIF ID
SOL ID
Scheme Code
CCY
A/c. Name
A/c. Opening Date
Document Date
Drawing Power Indicator
Max. Allowed Limit
2. Click on ""Continue"" button"
,,,,,,,,5,"Navigate to ""Additional Details- General Details"" Tab"
,,,,,,,,6,"Fill in Mandatory field
Charge Level Code"
,,,,,,,,7,"Navigate to ""Additional Details"" Interest Details Tab"
,,,,,,,,8,"Fill in Mandatory fields:
Interest Credit A/c. ID
Interest Debit A/c. ID
Interest Calculation Frequency (Cr.)
Next Interest Calculation Date (Cr.)
Interest Calculation Frequency (Dr.)
Next Interest Calculation Date (Dr.)
Click on ""Continue"" button"
,,,,,,,,9,Fill in Non-Mandatory Tabs if required
,,,,,,,,10,"Click on ""Submit"" button"
Alerts,SMS,As-is,Alerts_ODA_Retail_Verify_OverdraftAccountOpenning_Unsecured_85026_EGP_ByChecker_C2,Checker,"Validate that checker can authorize ""85026"" Un secured Overdraft Account and validate financial impact from customers side and bank side",Creation of Overdraft Limit for the Subscribed customer,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Branch Checker user Logged into the system
,,,,,,,,2,"Navigate to ""Verify Overdraft"" Screen"
,,,,,,,,3,Enter Overdraft Account ID
,,,,,,,,4,"Click on ""Submit"" button"
Alerts,SMS,ASST_ALERT_08,Alerts_SMS_RealTime_CreationOfOverdraftLimit_C3,User,Validate that the customer receives SMS immediately after a Creation of Overdraft Limit,Creation of Overdraft Limit for the customer,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Validate that the customer receives SMS after a Creation of Overdraft Limit
Alerts,SMS,ASST_ALERT_30,Alerts_SMS_OverdraftExposureIsExcessOrOverLimit_COB_E1,User,Validate that the  customer receives SMS to be notified in case Loan Overdraft Exposure is in excess over limit,Overdraft Exposure is in excess over limit for the  customer_COB is Run,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Run Weekly COB
,,,,,,,,2,Validate  Customer is Over Limit
,,,,,,,,3,Validate that the subscribed SMS customer receives a weekly SMS to be notified in case Loan Overdraft Exposure is in excess over limit
Alerts,SMS,"ASST_ALERT_12
ASST_ALERT_17",Alerts_SMS_SubscribedCustomer_UpcomingDueDetails_COB_F1,User,Validate that the subscribed SMS customer receives SMS to be Notified N days prior to due date about the upcoming due with due details,Upcoming Dues for the Subscribed customer_COB is Run,"1- Created Loan A/c. ID with payment due in 5 days
2- Mobile device and SIM Card
3- Subscribed CIF
4- Mobile number linked to CIF",1,Run COB End Of Day
,,,,,,,,2,Validate that the customer receives SMS to be Notified 5 days prior to due date about the upcoming due with due details
Alerts,SMS,ASST_ALERT_29,Alerts_SMS_SubscribedCustomer_LoanInstallmentOverdue_COB_H1,User,Validate that the subscribed SMS customer receives SMS to be notified in case Loan Installment is Overdue,Overdue Loan Installment for the Subscribed customer_COB is Run,"1- Created Loan A/c. ID with DPD from 1-60 days
2- Mobile device and SIM Card
3- Mobile number linked to CIF",2,Validate that the customer receives SMS to be notified in case Loan Installment is Overdue
Alerts,SMS,ASST_0084,Alerts_LAA_Retail_LoanRepayment_ManualRepayment_NormalRepayment_EGP_ByMaker_J1,Maker,Validate that maker can make schedule payment and repay the two first installments in case that customer repay the amount of the two next Installments,Creation and Disbursement of Loan account for the Subscribed customer,"1- Created Loan A/c. ID with overdue amount
2- Operative A/c. ID with a credit balance and no freeze instructions
3- Mobile device and SIM Card
4- Mobile number linked to CIF",1,Activation user Logged into the system
,,,,,,,,2,Navigate to Perform Loan Schedule Payment / PLSP Screen
,,,,,,,,3,"Select Entity Type
Loan A/c."
,,,,,,,,4,"Click on ""Go"" button"
,,,,,,,,5,"Click on ""Add"" button"
,,,,,,,,6,Enter the loan Account ID
,,,,,,,,7,"Fill in Mandatory fields/ Non mandatory (if required)
Loan A/c. ID
Value Date
Payment Amt.
Transaction Type"
,,,,,,,,8,"Click on ""Save and Preview"" button"
,,,,,,,,9,"Click on ""Submit"" button"
Alerts,SMS,ASST_0084,Alerts_LAA_Retail_Verify_LoanRepayment_ManualRepayment_NormalRepayment_EGP_ByChecker_J2,Checker,"Validate that checker can authorize scheduling payment, repaying the two first installmentsof the loan and validate that the amount of these two first installments are debited from customer side",Creation and Disbursement of Loan account for the Subscribed customer,"1- Created Loan A/c. ID with overdue amount
2- Operative A/c. ID with a credit balance and no freeze instructions
3- Mobile device and SIM Card
4- Mobile number linked to CIF",1,Activation user Logged into the system
,,,,,,,,2,Navigate to Verify Loan Payment / VLSP Screen
,,,,,,,,3,Enter Transaction ID
,,,,,,,,4,"Click on ""Go"" button"
,,,,,,,,5,Click on Submit button
,,,,,,,,6,"Validate Account is deducted successfully , Navigate to > Inquire on Ledger / ILE Screen
Enter the Account ID"
Alerts,SMS,ASST_ALERT_15,Alerts_SMS_RealTime_Repayments_COB_J3,User,Validate that the  customer receives SMS directly to be notified on any repayment done,Repayment from the customer_COB is Run,"1- Created Loan A/c. ID with overdue amount
2- Operative A/c. ID with a credit balance and no freeze instructions
3- Mobile device and SIM Card
4- Mobile number linked to CIF",1,Validate that the customer receives SMS directly to be notified on any repayment done
