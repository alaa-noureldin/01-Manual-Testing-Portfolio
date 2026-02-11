<details>
  <summary><b>First: Defect Report Creation Sample</b></summary>

  | Field              | Value                                                                 |
|--------------------|-----------------------------------------------------------------------|
| **Defect ID**      | HOR-18144                                                             |
| **Defect Title**   | SIT_Cycle1_Assets_Collateral_LinkCollateralToEntityID – Could not Modify Lien |
| **Severity**       | Medium                                                                |
| **Priority**       | Medium                                                                |
| **Assigned To**    | Dev Team                                                              |
| **Reporter**       | Testing Team                                                          |
| **Status**         | New / Open                                                            |

### Defect Description
Test steps:

| Step | Action                                                                 | Data / Input                          | Expected Result                                      | Actual Result              | Status  |
|------|------------------------------------------------------------------------|---------------------------------------|------------------------------------------------------|----------------------------|---------|
| 1    | Branch Maker user logs into the system                                 | Entity ID                             | User logged in successfully                          | (not provided)             | -       |
| 2    | Navigate to "Link Collateral to Entity ID / LCEI" screen               | -                                     | "Link Collateral to Entity ID / LCEI" screen opens successfully | (not provided)             | -       |
| 3    | 1. Fill mandatory fields: • Entity Type • Entity ID (A/c. ID)<br>2. Click "Go" button | Entity Type + Entity ID               | Values entered successfully<br>Data retrieved and displayed successfully | (not provided)             | -       |
| 4    | Edit Lien                                                              | -                                     | Lien is edited successfully                          | Couldn't Modify Lien       | **Failed** |

**Additional Notes:**
- As per **MRD ASST-0421**, Modify lien will be available on **LCEI** Menu.
- Couldn’t find Editing lien through this menu.

**Attachements:**
- Screenshots and/or videos to be added.

</details>

<details>
  <summary><b>Second: Defect Report Creation Sample</b></summary>

  | Field              | Value                                                                 |
|--------------------|-----------------------------------------------------------------------|
| **Defect ID**      | NBU2-2093                                                             |
| **Defect Title**   | SIT_Cycle1_Treasury_TreasuryTrader_Deal Verify screen generates an error |
| **Severity**       | High                                                                  |
| **Priority**       | Medium                                                                |
| **Assigned To**    | Dev Team                                                              |
| **Reporter**       | Testing Team                                                          |
| **Status**         | New / Open                                                            |

### Defect Description

**Test steps:**

| Step | Action                                                                 | Data / Input                              | Expected Result                                           | Actual Result              | Status  |
|------|------------------------------------------------------------------------|-------------------------------------------|-----------------------------------------------------------|----------------------------|---------|
| 1    | Treasury Trader user logs into the system                              | Valid credentials                         | User logged in successfully                               | (not provided)             | -       |
| 2    | Navigate to Treasury Deal Entry / Maintenance screen                  | -                                         | Treasury Deal screen opens successfully                   | (not provided)             | -       |
| 3    | Create or open a Deal (e.g., MM/FX/Loan/Swap) and fill mandatory fields | Deal Type, Counterparty, Amount, Rate, etc. | Deal details entered successfully                         | (not provided)             | -       |
| 4    | Click "Verify" button (or equivalent action to verify the deal)       | -                                         | Deal is verified successfully (no errors, proceeds to authorization/save) | Screen generates an error | **Failed** |

**Additional Notes:**
- Error occurs when attempting to verify the deal on the Treasury Deal Verify screen.
- Issue observed across different deal types (MM/FX/Loan/Swap).

**Attachements:**
- Screenshots and/or videos to be added.

</details>
