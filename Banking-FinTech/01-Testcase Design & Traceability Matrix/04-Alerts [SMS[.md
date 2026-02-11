Stream,Component,Req-ID,Testcase Name,Precondition,Objective,Label,Actor,Test data,Step-Nr,Test Steps,Expected Result
Alerts,SMS,As-is,Alerts_LAA_Retail_PerformLoanDisbursement_EGP_ByMaker_A1,Creation and Disbursement of Loan account for the Subscribed customer,Validate that maker can perform loan disbursement for EGP loan account,,Maker,"1- Created Loan A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Activation user Logged into the system,Activation User logged in successfully
,,,,,,,,,2,Navigate to PLD Screen,"""Perform Loan Disbursement / PLD"" Screen will be opened successfully"
,,,,,,,,,3,"Navigate to ""Disbursement Details"" Tab",Disbursement Details Tab will be displayed
,,,,,,,,,4,"1-Fill in Mandatory fields
A/c. ID
Transaction Type: Transfer
Value Date
Disbursement Amt
2-Click Continue",Values entered successfully
,,,,,,,,,5,Navigate to Loan Fees Details,Loan Fees Details will be displayed
,,,,,,,,,6,Fill in Mandatory fields,Values entered successfully
,,,,,,,,,7,"Click on ""Submit"" Button",Loan Disbursement done successfully and submitted for verification
Alerts,SMS,As-is,Alerts_LAA_Retail_Verify_LoanDisbursement_EGP_ByChecker_A2,Creation and Disbursement of Loan account for the Subscribed customer,Validate that checker can verify on perform loan disbursement for EGP loan account,,Checker,"1- Created Loan A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Activation user Logged into the system,Activation User logged in successfully
,,,,,,,,,2,Navigate to VLDR Screen,"""Verify Loan Disbursement or Reversal / VLDR"" Screen will be opened successfully"
,,,,,,,,,3,Enter A/c. ID,The screen is opened with all the details of the account in dimmed mode
,,,,,,,,,4,"Click on ""Submit"" button","1- Loan Account is Disbursement successfully
2. Loan amount credited successfully to Customer account
3. Fees amount debited successfully from Customer account"
Alerts,SMS,ASST_ALERT_02,Alerts_SMS_RetailCustomer_RealTime_LoanDisbursement_By User_A3,Creation and Disbursement of Loan account,Validate that the customer receives SMS immediately after a Loan Disbursement,,User,"1- Created Loan A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Customer receives SMS after a loan disbursement,"Validation done successfully and customer receives the below SMS directly after a Loan Disbursement:

Congrats! Your Personal Finance Program from ALEXBANK has been activated and credited into your current account today. We remind you to pay the installments according to the agreement terms started on (DD/MM/YYYY). 

You can easily track your loan details through our Internet and Mobile Banking service. For registration please call 19033

مبروك! تم تفعيل برنامج التمويل الشخصي الخاص بكم من بنك الإسكندرية وإضافته للحساب الجاري اليوم ونذكركم بسداد الأقساط وفقا للتعاقد
 (DD/MM/YYYY) الذي بدأ في يوم   

ويمكنكم متابعة تفاصيل التمويل بكل سهولة مع خدمة الانترنت والموبايل البنكي، للاشتراك اتصل ب19033"
Alerts,SMS,ASST_0110,Alerts_ODA_Retail_ModifySanctionLimit_EGP_ByMaker_B1,Modification of Overdraft Limit for the Subscribed customer,Validate that maker can modify sanctioned limit for Retail OVD Acc,,Maker,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Branch Maker user Logged into the system,User logged in successfully
,,,,,,,,,2,"Navigate to ""Modify Sanction Limits / MSL"" Screen","""Modify Sanction Limits / MSL"" Screen will be opened successfully"
,,,,,,,,,3,Enter A/c. ID,Values entered successfully
,,,,,,,,,4,Click on Go button,The screen will be displayed with all details in editable mode
,,,,,,,,,5,"Click on ""Edit Icon"" in the record inside Sanction Limit Details Table",The screen of the record will be displayed with all details in editable mode
,,,,,,,,,6,"1- Modify the following Dropdown lists/fields:
2- Select for Edit: Yes
3- Sanction Limit",Values modified successfully
,,,,,,,,,7,Click on Update button,User will be directed to Sanction Limit Details Table
,,,,,,,,,8,Click on Submit button,Sanctioned limit will be modified and submitted for verification
Alerts,SMS,ASST_0110,Alerts_ODA_Retail_Verify_ModifySanctionLimit_EGP_ByChecker_B2,Modification of Overdraft Limit for the Subscribed customer,Validate that checker can verify edited sanctioned limit for Retail OVD Acc,,Checker,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Branch Checker user Logged into the system,User logged in successfully
,,,,,,,,,2,"Navigate to ""Verify Sanction Limits / VSL"" Screen","""Verify Sanction Limits / VSL"" Screen will be opened successfully"
,,,,,,,,,3,Enter A/c. ID,Values entered successfully
,,,,,,,,,4,Click on Go button,The screen will be displayed with all details in dimmed mode
,,,,,,,,,5,Click on Update button,Sanctioned limit modified successfully
Alerts,SMS,ASST_ALERT_36,Alerts_SMS_RealTime_ModificationOfOverdraftLimit_ByUser_B3,Modification of Overdraft Limit for the customer,Validate that the subscribed SMS customer receives SMS immediately after a Modification of Overdraft Limit,,User,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Validate that the customer receives SMS after a Modification of Overdraft Limit,"Validation done successfully and customer receives the below SMS directly after a Modification of Overdraft Limit:

Dear valued customer,

Please note that your overdraft limit modification request has been activated. Your new limit is EGP XX:XX

You can easily track your facility details through our Mobile & Internet Banking service. For registration please call 19033

عميلنا العزيز

تم تنفيذ طلبكم الخاص بحساب التسهيل الائتمانى من بنك الإسكندرية تم تعديل الحد الائتمانى الخاص بكم ليصل إلى XX:XX جم     

ويمكنكم متابعة تفاصيل التسهيل بكل سهولة مع خدمة الموبايل والانترنت البنكي، للاشتراك اتصل ب 19033"
Alerts,SMS,As-is,Alerts_ODA_Retail_OpenOverdraftAccount_Unsecured_85026_EGP_ByMaker_C1,Creation of Overdraft Limit for the Subscribed customer,"Validate that maker can create Un secured Overdraft Staff Account ""85026"" in EGP Currency",,Maker,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Branch Maker user Logged into the system,User logged in successfully
,,,,,,,,,2,"Navigate to ""Open Overdraft Account / OOA"" Screen","""Open Overdraft Account / OOA"" Screen will be opened successfully"
,,,,,,,,,3,"Navigate to ""Basic A/c. Details"" Tab",Basic A/c. Details Tab will be displayed
,,,,,,,,,4,"1-Fill in Mandatory fields
CIF ID
SOL ID
Scheme Code
CCY
A/c. Name
A/c. Opening Date
Document Date
Drawing Power Indicator
Max. Allowed Limit
2. Click on ""Continue"" button","Values entered successfully
User will be directed to ""Additional Details- General Details"" Tab"
,,,,,,,,,5,"Navigate to ""Additional Details- General Details"" Tab","""Additional Details- General Details"" Tab will be displayed"
,,,,,,,,,6,"Fill in Mandatory field
Charge Level Code",Values entered successfully
,,,,,,,,,7,"Navigate to ""Additional Details"" Interest Details Tab",Interest Details Tab will be displayed successfully
,,,,,,,,,8,"Fill in Mandatory fields:
Interest Credit A/c. ID
Interest Debit A/c. ID
Interest Calculation Frequency (Cr.)
Next Interest Calculation Date (Cr.)
Interest Calculation Frequency (Dr.)
Next Interest Calculation Date (Dr.)
Click on ""Continue"" button",Values entered successfully
,,,,,,,,,9,Fill in Non-Mandatory Tabs if required,Values entered successfully
,,,,,,,,,10,"Click on ""Submit"" button",Overdraft Account is created successfully and submitted for verification
Alerts,SMS,As-is,Alerts_ODA_Retail_Verify_OverdraftAccountOpenning_Unsecured_85026_EGP_ByChecker_C2,Creation of Overdraft Limit for the Subscribed customer,"Validate that checker can authorize ""85026"" Un secured Overdraft Account and validate financial impact from customers side and bank side",,Checker,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Branch Checker user Logged into the system,User logged in successfully
,,,,,,,,,2,"Navigate to ""Verify Overdraft"" Screen","""Verify Overdraft"" Screen will be opened successfully"
,,,,,,,,,3,Enter Overdraft Account ID,The screen is opened with all the details of the account in dimmed mode
,,,,,,,,,4,"Click on ""Submit"" button",Overdraft Account is Verified successfully
Alerts,SMS,ASST_ALERT_08,Alerts_SMS_RealTime_CreationOfOverdraftLimit_C3,Creation of Overdraft Limit for the customer,Validate that the customer receives SMS immediately after a Creation of Overdraft Limit,,User,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",1,Validate that the customer receives SMS after a Creation of Overdraft Limit,"Validation done successfully and customer receives the below SMS directly after a Creation of Overdraft Limit:

Congrats! Your overdraft account from ALEXBANK has been activated according to the agreement terms starting from (DD/MM/YYYY). 

You can easily track your facility details through our Mobile & Internet Banking service. For registration please call 19033

مبروك! تم تفعيل حساب التسهيل الائتماني من بنك الإسكندرية وفقا للتعاقد الذى بدأ  فى يوم (DD/MM/YYYY)  

ويمكنكم متابعة تفاصيل التسهيل بكل سهولة مع خدمة الموبايل والانترنت البنكي، للاشتراك اتصل ب 19033"
Alerts,SMS,ASST_ALERT_30,Alerts_SMS_OverdraftExposureIsExcessOrOverLimit_COB_E1,Overdraft Exposure is in excess over limit for the  customer_COB is Run,Validate that the  customer receives SMS to be notified in case Loan Overdraft Exposure is in excess over limit,,User,,1,Run Weekly COB,
,,,,,,,,,2,Validate  Customer is Over Limit,
,,,,,,,,"1- Created OVD A/c. ID
2- Mobile device and SIM Card
3- Mobile number linked to CIF",3,Validate that the subscribed SMS customer receives a weekly SMS to be notified in case Loan Overdraft Exposure is in excess over limit,"Dear valued customer,

Kindly settle the excess on your overdraft account.

You can easily track your facility details through our Mobile & Internet Banking service. For registration please call 19033.

عميلنا العزيز، يرجى سرعة سداد التجاوز عن الحد الائتماني لحساب التسهيل.

يمكنكم متابعة تفاصيل التسهيل بكل سهولة مع خدمة الموبايل والانترنت البنكي، للاشتراك اتصل ب 19033"
Alerts,SMS,"ASST_ALERT_12
ASST_ALERT_17",Alerts_SMS_SubscribedCustomer_UpcomingDueDetails_COB_F1,Upcoming Dues for the Subscribed customer_COB is Run,Validate that the subscribed SMS customer receives SMS to be Notified N days prior to due date about the upcoming due with due details,,User,,1,Run COB End Of Day,
,,,,,,,,"1- Created Loan A/c. ID with payment due in 5 days
2- Mobile device and SIM Card
3- Subscribed CIF
4- Mobile number linked to CIF",2,Validate that the customer receives SMS to be Notified 5 days prior to due date about the upcoming due with due details,"Validation done successfully and customer receives the below SMS to be Notified 5 days prior to due date about the upcoming due with due details:

عميلنا العزيز،

بقيمة(DD/MM/YYYY)نذكر سيادتكم بسداد قيمة قسط التمويل الخاص بكم والمستحق فى  

   XX:XXجم   

ويمكنكم متابعة تفاصيل التمويل بكل سهولة مع خدمة الانترنت والموبايل البنكي، للاشتراك اتصل ب 19033

Dear valued customer, 

This is to remind with loan installment due EGP XX:XX. We appreciate your promt paying by (DD/MM/YYYY)

For more information  please call 19033"
Alerts,SMS,ASST_ALERT_29,Alerts_SMS_SubscribedCustomer_LoanInstallmentOverdue_COB_H1,Overdue Loan Installment for the Subscribed customer_COB is Run,Validate that the subscribed SMS customer receives SMS to be notified in case Loan Installment is Overdue,,User,"1- Created Loan A/c. ID with DPD from 1-60 days
2- Mobile device and SIM Card
3- Mobile number linked to CIF",2,Validate that the customer receives SMS to be notified in case Loan Installment is Overdue,"Dear valued customer,

Kindly settle the overdues on your loan account # <ACCT_NO

You can easily track your loan details through our Mobile & Internet Banking service. For registration please call 19033

عميلنا العزيز، يرجى سرعة سداد المتأخرات عن حساب التمويل  .#<ACCT_NO> 

 يمكنكم متابعة تفاصيل التمويل بكل سهولة مع خدمة الموبايل والانترنت البنكي، للاشتراك اتصل ب 19033"
Alerts,SMS,ASST_0084,Alerts_LAA_Retail_LoanRepayment_ManualRepayment_NormalRepayment_EGP_ByMaker_J1,Creation and Disbursement of Loan account for the Subscribed customer,Validate that maker can make schedule payment and repay the two first installments in case that customer repay the amount of the two next Installments,,Maker,"1- Created Loan A/c. ID with overdue amount
2- Operative A/c. ID with a credit balance and no freeze instructions
3- Mobile device and SIM Card
4- Mobile number linked to CIF",1,Activation user Logged into the system,Activation User logged in successfully
,,,,,,,,,2,Navigate to Perform Loan Schedule Payment / PLSP Screen,"""Perform Loan Schedule Payment / PLSP"" Screen will be opened successfully"
,,,,,,,,,3,"Select Entity Type
Loan A/c.",Loan A/c. will be selected successfully
,,,,,,,,,4,"Click on ""Go"" button","""Add"" button will be clickable"
,,,,,,,,,5,"Click on ""Add"" button",Screen will be displayed to add a new record
,,,,,,,,,6,Enter the loan Account ID,Loan A/c. will be selected successfully
,,,,,,,,,7,"Fill in Mandatory fields/ Non mandatory (if required)
Loan A/c. ID
Value Date
Payment Amt.
Transaction Type",Values entered successfully
,,,,,,,,,8,"Click on ""Save and Preview"" button",Payment List will be displayed Successfully
,,,,,,,,,9,"Click on ""Submit"" button",Record is submitted Successfully for verification
Alerts,SMS,ASST_0084,Alerts_LAA_Retail_Verify_LoanRepayment_ManualRepayment_NormalRepayment_EGP_ByChecker_J2,Creation and Disbursement of Loan account for the Subscribed customer,"Validate that checker can authorize scheduling payment, repaying the two first installmentsof the loan and validate that the amount of these two first installments are debited from customer side",,Checker,"1- Created Loan A/c. ID with overdue amount
2- Operative A/c. ID with a credit balance and no freeze instructions
3- Mobile device and SIM Card
4- Mobile number linked to CIF",1,Activation user Logged into the system,Activation User logged in successfully
,,,,,,,,,2,Navigate to Verify Loan Payment / VLSP Screen,"""Verify Loan Payment / VLSP"" Screen will be opened successfully"
,,,,,,,,,3,Enter Transaction ID,Values entered successfully
,,,,,,,,,4,"Click on ""Go"" button",The screen is opened with all the details of the account in dimmed mode
,,,,,,,,,5,Click on Submit button,Record is submitted Successfully
,,,,,,,,,6,"Validate Account is deducted successfully , Navigate to > Inquire on Ledger / ILE Screen
Enter the Account ID","1- The two first installments is repaid successfully
2- The amount of the two first installments is debited from customer side successfully and credited to bank account successfully"
Alerts,SMS,ASST_ALERT_15,Alerts_SMS_RealTime_Repayments_COB_J3,Repayment from the customer_COB is Run,Validate that the  customer receives SMS directly to be notified on any repayment done,,User,"1- Created Loan A/c. ID with overdue amount
2- Operative A/c. ID with a credit balance and no freeze instructions
3- Mobile device and SIM Card
4- Mobile number linked to CIF",1,Validate that the customer receives SMS directly to be notified on any repayment done,"Validation done successfully and customer receives the below SMS directly to be notified on any repayment done:

عميلنا العزيز

تم خصم مبلغ XX:XX جم /سداد قسط التمويل فى (DD/MM/YYYY). 

ويمكنكم متابعة تفاصيل التمويل بكل سهولة مع خدمة الانترنت والموبايل البنكي، للاشتراك اتصل ب 19033                                                                                                                                                                  Dear Valued Customer

Your account has been debited EGP XX:XX for your loan installment on (DD/MM/YYYY).

You can easily track your loan details through our Mobile & Internet Banking service. For registration please call 19033"
