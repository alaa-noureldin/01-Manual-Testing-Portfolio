<details>
  <summary><b>T-Bills</b></summary>

  | Stream | Component | Req-ID | Testcase Name | Actor | Objective | Test data | Step | Test Steps | Expected Result |
|--------|-----------|--------|---------------|-------|-----------|-----------|------|------------|-----------------|
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBills_Definition_Create_EGP_HFT_Maker_A1 | Maker | Create Security Definition FO | Valid Login Credentials | 1 | Login to Treasury Desktop App with Valid user name and password | Logged in successfully |
| > | > | > | > | > | > | > | 1 | Navigate to Securities Tab -> Definition -> Security Definition | Screen Opened successfully |
| > | > | > | > | > | > | > | 1 | Check that all these fields are filled by Default and also editable :<br>-Trade Quantitative Method: Face Value<br>-Issue Currency: EGP<br>ISIN :- to be Fulfilled<br>-Redemption Value: 100<br>-Definition Status: Open<br>-Price Quotaion Method: Clean Price (%)<br>-Issue Date : Today's date<br>-When Issued: None<br>-MTM Valuation: External<br>-Entity Perm Group : ABE by default<br>-Security Status: Unsecured<br>-Short Sales: Allowed<br>- WTH tax: yes<br>- PCT : 20%<br>-Valuation Method: Original Face<br>-Minimum Amount: 25000<br>-Quantity Multiple: 1<br>-Realization Method: WAP_Position<br>-Date to realize : SETT Date<br>-Applicabilitiy Flags : HFT category<br>-Both Premium and Discount on Net Basis Flag | All these fields should be auto filled and editable. |
| > | > | > | > | > | > | > | 1 | Input the mandatory fields<br>-Security ID<br>-Security Type: Bill<br>-User Type: T-Bill<br>-Select value from Effective Yield Method DDL : Bond-Equivalent<br>-Coupon Frequency: Bullet<br>-Effective Yield Basis: A/365<br>-Yield Method: Discount-Yield<br>-Float/Fixed: Fixed [it's filled by default also]<br>-Maturity Date<br>-Yield Basis<br>-Contract Rate:0<br>-Select Issuer<br>-Description<br>-Select HFT category from Amortization section | Fields are filled successfully |
| > | > | > | > | > | > | > | 1 | Navigate to Curves /Rating and Reselect Explicit Curve | Security Status is Sufficent and can be saved |
| > | > | > | > | > | > | > | 1 | Click Save | Security definition saved successfully |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBill_Definition_Approve_EGP_HFT_Checker_A2 | Checker | Verify Created Security Definition FO | Created Security Definition | 2 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 2 | Navigate to Securities Tab -> Definition -> Security Definition | Screen Opened successfully |
| > | > | > | > | > | > | > | 2 | Click on Unapproved button on the Upper page menu | All unapproved Security Definitions will be displayed |
| > | > | > | > | > | > | > | 2 | Double click on the Security definition | Deal details page is displayed |
| > | > | > | > | > | > | > | 2 | Check and Review data | Deal data is displayed successfully |
| > | > | > | > | > | > | > | 2 | Click on Approve | Definition approved |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBill_Bank_BuyDeal_HFT_Create_Primary_EGP_HFT_Maker_A3 | Maker | Create Tbill Primary Buy Deal | Valid Login Credentials | 3 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 3 | Navigate to Securities Tab -> Securities Buy/Sell | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 3 | Enter All Mandatory Data :<br>-Enter Counterparty [Bank]<br>-Select Security ID [Tbill]<br>- Select Buy<br>- Enter Original Face Value[Amount] Mulyiple 25000<br>- price<br>- settlement date<br>-Click on Insert | Selecting Security will auto fill most of the fields<br>Deal is inserted successfully<br>Deal Status will be Incomplete |
| > | > | > | > | > | > | > | 3 | Check limits |  |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBill_Bank_BuyDeal_Complete_Primary_EGP_HFT_Checker_A4 | Checker | Complete Primary Buy Deal | Created deal | 4 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 4 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 4 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 4 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 4 | Review Deal Details | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 4 | Check Limit | Limits for deal are displayed with status Ok [Not Breached] |
| > | > | > | > | > | > | > | 4 | Click on Complete | Deal Status will be Completed |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_BO_TBill_Bank_BuyDeal_Review&Update_Primary_EGP_HFT_Maker_A5 | Maker | Review/Update Primary Buy Deal | Created deal | 5 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 5 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 5 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 5 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 5 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 5 | Update Settelment tab | Settlement tab updated successfully |
| > | > | > | > | > | > | > | 5 | Check Limit | Limits for deal are displayed with status Ok [Not Breached] |
| > | > | > | > | > | > | > | 5 | Click on Update | Deal is Updated Successfully |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_BO_TBill_Bank_BuyDeal_Accept_Primary_EGP_HFT_Checker_A6 | Checker | Accept Primary Buy Deal | Completed deal | 6 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 6 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 6 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 6 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 6 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 6 | Check Limit | Limits for deal are displayed with status Ok [Not Breached] |
| > | > | > | > | > | > | > | 6 | Click on Accept | Status changed to Accepted |
| > | > | > | > | > | > | > | 6 | Navigate to Views tab -> EFT Message | System generates Payment Swift MT541 |
| > | > | > | > | > | > | > | 6 | Review Swift & Release Swift | Swift is released |
| > | > | > | > | > | > | > | 6 | Run COB end of day | COB run successfully |
| > | > | > | > | > | > | > | 6 | Navigate to Views tab -> GL Journal Entries | Check Accounting entries at buy date :<br>DR:Tbill Asset with the face Value [Held to Maturity GL]<br>CR: Accrual Bill Interest<br>CR : Nostro with Settlemet<br>Daily Accual :<br>DR : Accrual with [1 day interest value]<br>CR : Tbill income with [1 day interest value]<br>DR : Expenses with 20% from 1 day interest [ 1 day interest leh calculation not linear]<br>CR : Tax accrual with 20 % from 1 day interest |
| > | > | > | > | > | > | > | 6 | Run COB to maturity date | COB run successfully |
| > | > | > | > | > | > | > | 6 | Navigate to Views tab -> GL Journal Entries | Check Accounting entries After Maturity Date:<br>DR: Nostro Account with face value<br>CR:Tbill Asset with face value<br>DR : Tax accrual with 20% from the 1 m [total interest]<br>CR : Nostro Account with 20% from the 1 m [total interest] |
| Tbills | Tbills | MRD.FT.067 | Treasury_Securities_BO_TBill_Bank_BuyDeal_CheckAccounting Entries__EOD_Primary_USD_HTM_Checker_A7 | Checker | Checking Accounting entries for Buy deal BO | Created deal | 7 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 7 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 7 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 7 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 7 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 7 | Run COB end of day | COB run successfully |
| > | > | > | > | > | > | > | 7 | Navigate to Views tab -> GL Journal Entries | Check Accounting entries at buy date :<br>DR:Tbill Asset with the face Value [Held to Maturity GL]<br>CR: Accrual Bill Interest<br>CR : Nostro with Settlemet<br>Daily Accual :<br>DR : Accrual with [1 day interest value]<br>CR : Tbill income with [1 day interest value]<br>DR : Expenses with 20% from 1 day interest [ 1 day interest leh calculation not linear]<br>CR : Tax accrual with 20 % from 1 day interest |
| Tbills | Tbills | MRD.FT.067 | Treasury_Securities_BO_TBill_Bank_BuyDeal_CheckAccounting Entries_AtMaturity_Primary_USD_HTM_Checker_A8 | Checker | Checking Accounting entries for Buy deal BO | Created deal | 8 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 8 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 8 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 8 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 8 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 8 | Run COB to maturity date | COB run successfully |
| > | > | > | > | > | > | > | 8 | Navigate to Views tab -> GL Journal Entries | Check Accounting entries After Maturity Date:<br>DR: Nostro Account with face value<br>CR:Tbill Asset with face value<br>DR : Tax accrual with 20% from the 1 m [total interest]<br>CR : Nostro Account with 20% from the 1 m [total interest] |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBill_Bank_SellDeal_Create_Secondary_EGP_BeforeMaturity_Fully_Maker_B1 | Maker | Create a Tbill Sell Deal Secondary EGP before Maturity Date | Valid Login Credentials | 9 | [Precondition] Create, Complete and accept a Tbill Buy Deal Secondary EGP from Bank with Maturity after 2 Months, Today's date is before Maturity Date |  |
| > | > | > | > | > | > | > | 9 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 9 | Navigate to Securities Tab -> Securities Buy/Sell | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 9 | Click on Buy Button to change it to Sell | Deal is changed to be a Sell Deal |
| > | > | > | > | > | > | > | 9 | Enter All Mandatory Data :<br>-Enter Counterparty [Bank]<br>-Select Security ID [Tbill]<br>- Enter Original Face Value[Same Amount as the buy amount] Mulyiple 25000<br>- price<br>- settlment date<br>-Click on Insert | Selecting Security will auto fill most of the fields<br>Sell Deal is inserted successfully<br>Sell Deal Status will be Incomplete |
| > | > | > | > | > | > | > | 9 | Check limits | Limits are checked successfully and in Status OK |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBill_Bank_SellDeal _Complete_Secondary_EGP_BeforeMaturity_Fully_Checker_B2 | Checker | Complete a Tbill Sell Deal Secondary EGP before Maturity Date | Created deal | 10 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 10 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 10 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 10 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 10 | Review Deal Details | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 10 | Check Limit | Limits for deal are displayed with status Ok [Not Breached] |
| > | > | > | > | > | > | > | 10 | Click on Complete | Deal Status will be Completed |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_BO_TBill_Bank_SellDeal_Review&Update_Secondary_EGP_BeforeMaturity_Fully_Maker_B3 | Maker | Review/Update a Tbill Sell Deal Secondary EGP before Maturity Date | Created deal | 11 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 11 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 11 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 11 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 11 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 11 | Update Settlment | Settlement tab updated successfully |
| > | > | > | > | > | > | > | 11 | Check Limit | Limits for deal are displayed with status Ok [Not Breached] |
| > | > | > | > | > | > | > | 11 | Click on Update | Deal is Updated Successfully |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_BO_TBill_Bank_SellDeal_Accept_Secondary_EGP_BeforeMaturity_Fully_Checker_B4 | Checker | Accept a Tbill Sell Deal Secondary EGP before Maturity Date | Completed deal | 12 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 12 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 12 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 12 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 12 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 12 | Check Limit | Limits for deal are displayed with status Ok [Not Breached] |
| > | > | > | > | > | > | > | 12 | Click on Accept | Status changed to Accepted |
| > | > | > | > | > | > | > | 12 | Navigate to Views tab -> EFT Message | System generates Swift MT543 |
| > | > | > | > | > | > | > | 12 | Review and Release Swift to swift Alliance | Swift is released |
| > | > | > | > | > | > | > | 12 | Run COB end of day | COB run successfully |
| > | > | > | > | > | > | > | 12 | Navigate to Views tab -> GL Journal Entries | Check Accounting entries at sell day<br>CR:Tbill Asset with the face Value<br>DR: Accrual Bill Interest<br>DR : Nostro with Settlemet<br>Daily Accual :<br>DR : TAX ACCRUAL with 20% Ffor keeping period<br>DR Tax capital gain Difference between accrued and (sell-buy)<br>CR : Nostro |
| Tbills | Tbills | MRD.FT.002 | Treasury_Securities_BO_TBill_Bank_SellDeal_CheckAccountingEntries_EOD_Secondary_EGP_BeforeMaturity_Fully_Checker_B5 | Checker | Checking Accounting entries for Sell deal BO | Created deal | 13 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 13 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 13 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 13 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 13 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 13 | Run COB end of day | COB run successfully |
| > | > | > | > | > | > | > | 13 | Navigate to Views tab -> GL Journal Entries | Check Accounting entries at sell day<br>CR:Tbill Asset with the face Value<br>DR: Accrual Bill Interest<br>DR : Nostro with Settlemet<br>Daily Accual :<br>DR : Accrual with [1 day interest value]<br>CR : Tbill income with [1 day interest value]<br>DR : Expenses with 20% from 1 day interest [ 1 day interest leh calculation not linear]<br>CR : Tax accrual with 20 % from 1 day interest |
| Tbills | Tbills | MRD.FT.020 | Treasury_Securities_FO_TBill_Bank_BuyDeal_Delete_Secondary_EGP_F1 | Maker | Delete Tbill buy deal | Created Buy Deal | 14 | [Precondition] Make a buy deal from bank and complete the whole process |  |
| > | > | > | > | > | > | > | 14 | Login to Treasury Desktop App with Valid user name and password | Logged in successfully |
| > | > | > | > | > | > | > | 14 | Navigate to Deal Blotter | Screen Opened successfully |
| > | > | > | > | > | > | > | 14 | Check Securities Checkbox and enter specific data for the wanted deal and click fetch | Security deal needed will be displayed |
| > | > | > | > | > | > | > | 14 | Double Click on the needed Security Deal | Security Deal needed page will be displayed |
| > | > | > | > | > | > | > | 14 | Click on Delete Button | Button is clicked successfully |
| > | > | > | > | > | > | > | 14 | Select Reason and enter comments and click OK | Status changes to Deleted |
| Tbills | Tbills | MRD.FT.020 | Treasury_Securities_BO_TBill_Bank_Accept_Delete_Deal_Checker_EGP_F2 | Checker | Accept Deletion of Tbill deal | Deleted Deal | 15 | [Precondition] Delete buy Tbill Deal | Buy Tbill Deal Deleted |
| > | > | > | > | > | > | > | 15 | Login to Treasury Desktop App with Valid user name and password | Logged in successfully |
| > | > | > | > | > | > | > | 15 | Navigate to Deal Blotter | Screen Opened successfully |
| > | > | > | > | > | > | > | 15 | Check Securities Checkbox and enter specific data for the wanted deal and click fetch | Security deal needed will be displayed |
| > | > | > | > | > | > | > | 15 | Double Click on the needed Security Deal | Security Deal needed page will be displayed |
| > | > | > | > | > | > | > | 15 | Click Accept | Status changed to Deleted |
| Tbills | Tbills | MRD.FT.026 | Treasury_Securities_FO_TBill_Replace_Deal_Maker_G1 | Maker | Replace Tbill deal | Created Deal | 16 | [Precondition] Tbill buy or sell deal is created and accepted | Placement Fixed Deal created |
| > | > | > | > | > | > | > | 16 | Login to Treasury Desktop App with Valid user name and password | Logged in successfully |
| > | > | > | > | > | > | > | 16 | Navigate to Deal Blotter | Screen Opened successfully |
| > | > | > | > | > | > | > | 16 | Check Securities Checkbox and enter specific data for the wanted deal and click fetch | Security deal needed will be displayed |
| > | > | > | > | > | > | > | 16 | Double Click on the needed Security Deal | Security Deal needed page will be displayed |
| > | > | > | > | > | > | > | 16 | Click Replace | pop up appears |
| > | > | > | > | > | > | > | 16 | Select Reason and enter comments and click OK Enter data | A new deal is created with same values of the deleted deal |
| > | > | > | > | > | > | > | 16 | Click Insert | Status changed to Incomplete |
| Tbills | Tbills | MRD.FT.026 | Treasury_Securities_FO_TBill_Complete_Replace_Deal_Checker_G2 | Checker | Complete Replaced deal | Replaced Deal | 17 | [Precondition] Replace Buy/Sell Deal | Placement Fixed Deal replaced |
| > | > | > | > | > | > | > | 17 | Login to Treasury Desktop App with Valid user name and password | Logged in successfully |
| > | > | > | > | > | > | > | 17 | Navigate to Deal Blotter | Screen Opened successfully |
| > | > | > | > | > | > | > | 17 | Check Securities Checkbox and enter specific data for the wanted deal and click fetch | Security deal needed will be displayed |
| > | > | > | > | > | > | > | 17 | Double Click on the needed Security Deal Review deal data | Security Deal needed page will be displayed |
| > | > | > | > | > | > | > | 17 | Click on Complete | Status changed to Completed |
| > | > | > | > | > | > | > | 17 | Navigate to Audit Tab and check the deleted deal | Status deleted for old deal |
| Tbills | Tbills | MRD.FT.026 | Treasury_Securities_BO_TBill_Complete_Replace_Deal_Accept_Checker_G3 | Checker | Accept Replaced deal | Replaced Deal | 18 | [Precondition] Replace Buy/Sell Deal | Placement Fixed Deal replaced |
| > | > | > | > | > | > | > | 18 | Login to Treasury Desktop App with Valid user name and password | Logged in successfully |
| > | > | > | > | > | > | > | 18 | Navigate to Deal Blotter | Screen Opened successfully |
| > | > | > | > | > | > | > | 18 | Check Securities Checkbox and enter specific data for the wanted deal and click fetch | Security deal needed will be displayed |
| > | > | > | > | > | > | > | 18 | Double Click on the needed Security Deal | Security Deal needed page will be displayed |
| > | > | > | > | > | > | > | 18 | Click on Accept | Status changed to Accepted |
| > | > | > | > | > | > | > | 18 | move to eft message and check swift generation | Swift message is checked successfully |
| > | > | > | > | > | > | > | 18 | Navigate to Audit Tab and check the deleted deal | Status deleted for old deal |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBill_Update_Accepted_Deal_Maker_Negative | Maker | Validate that the system doesn't allow updating an accepted deal | Accepted deal | 19 | Create and accept Tbill Buy or Sell deal | Deal Created and accepted |
| > | > | > | > | > | > | > | 19 | Login to Treasury Desktop App with Valid user name and password | Logged in successfully |
| > | > | > | > | > | > | > | 19 | Navigate to Deal Blotter | Screen Opened successfully |
| > | > | > | > | > | > | > | 19 | Check Securities Checkbox and enter specific data for the wanted deal and click fetch | Security deal needed will be displayed |
| > | > | > | > | > | > | > | 19 | Double Click on the needed Security Deal | Security Deal needed page will be displayed |
| > | > | > | > | > | > | > | 19 | Amend/Update Fields | Fields cannot be ammended |
| > | > | > | > | > | > | > | 19 | insert botton to be dimmed | Insert button is dimmed |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBill_Create_Deal_NegativeAmount_Maker_Negative | Maker | Validate that negative amount is not accepted in FT | Valid Login credentials | 20 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 20 | Navigate to Securities Tab -> Securities Buy/Sell | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 20 | Enter All Mandatory Data :<br>-Enter Counterparty [Bank]<br>-Select Security [Tbill]<br>- Enter Original Face Value[ Negative Amount] | Selecting Security will auto fill most of the fields |
| > | > | > | > | > | > | > | 20 | Click Insert | Field will be red highlighted<br>Deal couldn't be inserted |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBill_BuyDeal_Create_DealDate>SettlementDate_EGP_Negative | Maker | Validate deal dates | Valid Login credentials | 21 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 21 | Navigate to Securities Tab -> Securities Buy/Sell | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 21 | Enter All Mandatory Data :<br>-Enter Counterparty [Bank]<br>-Select Security [Tbill]<br>- Enter Deal Date > SettlementDate | Selecting Security will auto fill most of the fields |
| > | > | > | > | > | > | > | 21 | Click Insert | Field will be red highlighted<br>Deal couldn't be inserted |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBill_BuyDeal_Create_SettlementDate>=MaturityDate_EGP_Negative | Maker | validate deal dates | Valid Login credentials | 22 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 22 | Navigate to Securities Tab -> Securities Buy/Sell | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 22 | Enter All Mandatory Data :<br>-Enter Counterparty [Bank]<br>-Select Security [Tbill]<br>- Enter SettlementDate >=MaturityDate | Selecting Security will auto fill most of the fields |
| > | > | > | > | > | > | > | 22 | Click Insert | Field will be red highlighted<br>Deal couldn't be inserted |
| Tbills | Tbills | MRD.FT.060 | Treasury_Securities_FO_TBill_BuyDeal_Create_SettlmentDate!<issueDate_EGP_Negative | Maker | Validate deal dates | Valid Login credentials | 23 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 23 | Navigate to Securities Tab -> Securities Buy/Sell | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 23 | Enter All Mandatory Data :<br>-Enter Counterparty [Bank]<br>-Select Security [Tbill]<br>- Enter settlmentDate! | Selecting Security will auto fill most of the fields |
| > | > | > | > | > | > | > | 23 | Click Insert | Field will be red highlighted<br>Deal couldn't be inserted |
| T-Bill | T-Bill | MRD.FT.002, MRD.FT.032, MRD.FT.034 | Treasury_TBill_BuyDeal_Create_Primary_EGP_OnTreasuryDesktopApp_ByFrontOffice_TBCDA1 | Front Office | Validate that the Front Office can buy T-Bill by inserting the deal. | T-Bill definition is created and verified. | 24 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 24 | Navigate to Securities Tab -> Securities Buy/Sell | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 24 | Enter All Mandatory Data :<br>-Enter Counterparty [Bank Customer]<br>-Select Security ID [Tbill]<br>- Select Buy<br>- Enter Original Face Value[Amount]<br>- price<br>- settlement date | Selecting Security will auto fill most of the fields |
| > | > | > | > | > | > | > | 24 | Check limits | Limit is okay |
| > | > | > | > | > | > | > | 24 | Click on "Insert" button | Deal is inserted successfully<br>Deal Status will be Incomplete |
| T-Bill | T-Bill | MRD.FT.002, MRD.FT.032, MRD.FT.034 | Treasury_TBill_BuyDeal_Complete_Primary_EGP_OnTreasuryDesktopApp_ByFrontOffice_TBCDA2 | Front Office | Validate that the Front Office complete T-Bill buy deal. | Buy T-Bill deal in insert phase and pending to be completed. | 25 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 25 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 25 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 25 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 25 | Review Deal Details | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 25 | Check Limit | Limits for deal are displayed with status Ok [Not Breached] |
| > | > | > | > | > | > | > | 25 | Click on Complete | Deal Status will be Completed |
| T-Bill | T-Bill | MRD.FT.002, MRD.FT.032, MRD.FT.034 | Treasury_TBill_BuyDeal_Review/Update_Primary_EGP_OnTreasuryDesktopApp_ByBackOffice_TBCDA3 | Back Office | Validate that the Back Office review and update T-Bill buy deal. | Buy T-Bill deal in complete phase and pending to be accepted. | 26 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 26 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 26 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 26 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 26 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 26 | Update LB settlement tab | Settlement tab updated successfully |
| > | > | > | > | > | > | > | 26 | Select an account number | Account number is selected successfully |
| > | > | > | > | > | > | > | 26 | Check Limit | Limits for deal are displayed with status Ok [Not Breached] |
| > | > | > | > | > | > | > | 26 | Click on Complete | Deal Status will be Completed |
| T-Bill | T-Bill | MRD.FT.002, MRD.FT.032, MRD.FT.034 | Treasury_TBill_BuyDeal_Accept_Primary_EGP_OnTreasuryDesktopApp_ByBackOffice_TBCDA4 | Back Office | Validate that the Back Office accept T-Bill buy deal. | Reviewed and updated Buy T-Bill deal and pending to be accepted. | 27 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 27 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 27 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 27 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 27 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 27 | Click on "Accept" button | Status changed to Accepted |
| > | > | > | > | > | > | > | 27 | Navigate to "Messages" | Messages opened successfully |
| > | > | > | > | > | > | > | 27 | Select "Local Banking messages" | Local Banking messages is selected successfully |
| > | > | > | > | > | > | > | 27 | Click on "Fetch" button | All deals are fetched successfully |
| > | > | > | > | > | > | > | 27 | Choose the created deal and validate on the account number | Account number is validated successfully |
| T-Bill | T-Bill | MRD.FT.002, MRD.FT.032, MRD.FT.034 | Treasury_TBill_BuyDeal_Validate_Primary_EGP_OnBankCoreWebApp_ByMaker_TBCDA5 | Maker | Validate that the maker will validated on the account number on Bank Core Web App | Accepted Buy T-Bill deal | 28 | Login to Bank Core Web App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 28 | Navigate to "IAL / Inquire on Account Ledger" menu | "IAL / Inquire on Account Ledger" menu is opened successfully |
| > | > | > | > | > | > | > | 28 | 1- Enter A/c. ID 2-Click on "" button | Account entered successfully. Transaction details are displayed successfully. |
| > | > | > | > | > | > | > | 28 | Validate that the amount is debited from the account and credited to the office account. | transaction is validated successfully |
| T-Bill | T-Bill | MRD.FT.002, MRD.FT.032, MRD.FT.034 | Treasury_TBill_SellDeal_Create_Secondary_EGP_OnTreasuryDesktopApp_ByFrontOffice_TBCDB1 | Front Office | Validate that the Front Office can sell T-Bill by inserting the deal. | T-Bill definition is created and verified. | 29 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 29 | Navigate to Securities Tab -> Securities Buy/Sell | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 29 | Enter All Mandatory Data :<br>-Enter Counterparty [Bank Customer]<br>-Select Security ID [Tbill]<br>- Select Buy<br>- Enter Original Face Value[Amount]<br>- price<br>- settlement date | Selecting Security will auto fill most of the fields |
| > | > | > | > | > | > | > | 29 | Check limits | Limit is okay |
| > | > | > | > | > | > | > | 29 | Click on "Insert" button | Deal is inserted successfully<br>Deal Status will be Incomplete |
| T-Bill | T-Bill | MRD.FT.002, MRD.FT.032, MRD.FT.034 | Treasury_TBill_SellDeal_Complete_Secondary_EGP_OnTreasuryDesktopApp_ByFrontOffice_TBCDB2 | Front Office | Validate that the Front Office complete T-Bill sell deal. | Buy T-Bill deal in insert phase and pending to be completed. | 30 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 30 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 30 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 30 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 30 | Review Deal Details | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 30 | Check Limit | Limits for deal are displayed with status Ok [Not Breached] |
| > | > | > | > | > | > | > | 30 | Click on Complete | Deal Status will be Completed |
| T-Bill | T-Bill | MRD.FT.002, MRD.FT.032, MRD.FT.034 | Treasury_TBill_SellDeal_Review/Update_Secondary_EGP_OnTreasuryDesktopApp_ByBackOffice_TBCDB3 | Back Office | Validate that the Back Office review and update T-Bill sell deal. | Buy T-Bill deal in complete phase and pending to be accepted. | 31 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 31 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 31 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 31 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 31 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 31 | Update LB settlement tab | Settlement tab updated successfully |
| > | > | > | > | > | > | > | 31 | Select an account number | Account number is selected successfully |
| > | > | > | > | > | > | > | 31 | Check Limit | Limits for deal are displayed with status Ok [Not Breached] |
| > | > | > | > | > | > | > | 31 | Click on Complete | Deal Status will be Completed |
| T-Bill | T-Bill | MRD.FT.002, MRD.FT.032, MRD.FT.034 | Treasury_TBill_SellDeal_Accept_Secondary_EGP_OnTreasuryDesktopApp_ByBackOffice_TBCDB4 | Back Office | Validate that the Back Office accept T-Bill sell deal. | Reviewed and updated Sell T-Bill deal and pending to be accepted. | 32 | Login to Treasury Desktop App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 32 | Navigate to Deal Blotter | Screen Opened successfully with Buy option as default |
| > | > | > | > | > | > | > | 32 | Filter by Securities | Only Securities Deals should be displayed |
| > | > | > | > | > | > | > | 32 | Double click on the Deal | Deal Details screen is opened successfully |
| > | > | > | > | > | > | > | 32 | Review Deal Details & Update details if needed | Deal Details are retrieved correctly |
| > | > | > | > | > | > | > | 32 | Click on "Accept" button | Status changed to Accepted |
| > | > | > | > | > | > | > | 32 | Navigate to "Messages" | Messages opened successfully |
| > | > | > | > | > | > | > | 32 | Select "Local Banking messages" | Local Banking messages is selected successfully |
| > | > | > | > | > | > | > | 32 | Click on "Fetch" button | All deals are fetched successfully |
| > | > | > | > | > | > | > | 32 | Choose the created deal and validate on the account number | Account number is validated successfully |
| T-Bill | T-Bill | MRD.FT.002, MRD.FT.032, MRD.FT.034 | Treasury_TBill_SellDeal_Validate_Secondary_EGP_OnBankCoreWebApp_ByMaker_TBCDB5 | Maker | Validate that the maker will validated on the account number on Bank Core Web App | Accepted Sell T-Bill deal | 33 | Login to Bank Core Web App with Valid user name and password | Logged in Successfully |
| > | > | > | > | > | > | > | 33 | Navigate to "IAL / Inquire on Account Ledger" menu | "IAL / Inquire on Account Ledger" menu is opened successfully |
| > | > | > | > | > | > | > | 33 | 1- Enter A/c. ID 2-Click on "" button | Account entered successfully. Transaction details are displayed successfully. |
| > | > | > | > | > | > | > | 33 | Validate that the amount is debited from the account and credited to the office account. | transaction is validated successfully |
</details>

<details>
  <summary><b>T-Bonds</b></summary>

  Here is how you use the project.
</details>

<details>
  <summary><b>Money Market - MM</b></summary>

  Here is how you use the project.
</details>

<details>
  <summary><b>Foregin Exchange - FX</b></summary>

  Here is how you use the project.
</details>

<details>
  <summary><b>Repo</b></summary>

  Here is how you use the project.
</details>
