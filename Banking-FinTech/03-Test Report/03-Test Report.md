# Test Report – UAT Cycle Overview

**Report Date:** [Insert Date – e.g., February 11, 2026]  
**Cycle:** UAT2  
**Prepared by:** Testing Team  
**Shared with:** Testing Team, Business Team, Development Team, IT Bank Core Team  

This report provides a quick snapshot of testing progress, focusing on:
- Outstanding defects distribution
- Severity breakdown
- High-impact defects linked to the largest number of test cases

### 1. Outstanding Defects by Owner vs Severity (UAT Cycle)

| Owner                  | Critical | High | Total |
|------------------------|----------|------|-------|
| Dev Team               | 38       | 32   | **70** |
| Business Team          | 19       | 9    | **28** |
| IT Bank Core Team      | 1        | 0    | **1**  |
| **Grand Total**        | **58**   | **41** | **99** |

### 2. Outstanding Defects by Severity (Overall)

| Severity   | Count of Issue Key |
|------------|--------------------|
| Critical   | 56                 |
| High       | 38                 |
| Medium     | 233                |
| Low        | 13                 |
| **Grand Total** | **340**       |

### 3. Test Cases Linked to Outstanding Defects (Top Impacting Defects)

| Defect ID   | Linked Test Cases | Test Summary / Module                                                                 | Severity  | Assigned To     |
|-------------|-------------------|---------------------------------------------------------------------------------------|-----------|-----------------|
| HOR-22527   | 61                | UAT2_automated assets classification from PL to NPL and vice versa (HACUPL menu)     | Critical  | Dev Team        |
| HOR-20925   | 55                | UAT2_business_cycle_crm_CIFCorporate Issue                                            | Critical  | Dev Team        |
| HOR-28481   | 35                | UAT2_risk file                                                                        | Critical  | Business Team   |
| HOR-22794   | 25                | UAT2_Assets_Business_Issues In PCA scheme                                             | High      | Dev Team        |
| HOR-25263   | 19                | Stamp duty and HDB fees issue                                                         | Critical  | Dev Team        |
| HOR-23014   | 10                | UAT2_Finance_report_ CUSTREP Menu reports are generated with one SOL ID              | Critical  | Dev Team        |

### Key Observations & Next Steps

- **Critical & High defects** total **99 open issues**, with **70 owned by the Dev Team**.
- The top 6 defects alone are blocking **205 test cases** — highest impact seen in:
  - Assets classification (automated PL ↔ NPL)
  - CRM/CIF corporate issues
  - Risk file
  - PCA scheme business issues
  - Stamp duty & HDB fees
  - Finance CUSTREP reports
- **Total open defects: 340** — majority are Medium severity, but Critical defects remain the main blockers for sprint completion.
- **Recommendation:** Prioritize resolution of **Critical defects** with the highest linked test case count (especially HOR-22527 and HOR-20925) to unblock significant test coverage.

**Note:** This is a sample/partial report format used for daily or weekly status sharing with testing and business teams to provide visibility on sprint progress and remaining work.

---

