# Beneficiary Claims Analysis Dashboard — PM-JAY 🏥

An interactive Tableau dashboard analyzing beneficiary claims under the **Pradhan Mantri Jan Arogya Yojana (PM-JAY)**, Ministry of Health & Family Welfare, Government of India. Data as on 20 May 2025.

## 🔍 Overview

This dashboard consolidates claims, approval, and processing data across hospitals, districts, TPAs, and policy years, enabling stakeholders to filter by **policy year, beneficiary district, hospital name/type, package specialty, TPA, identity status, and claim status** for detailed operational analysis.

**Snapshot:**
- **Total Claims:** 49,001
- **Total Claim Amount:** ₹200.76 Cr
- **Total Approved Amount:** ₹133.68 Cr (66.60% of claim amount)
- **Average Claim Amount:** ₹40,964 per claim
- **Average Approval %:** 66.60%
- **Average Processing Delay:** 19.37 days

## ✨ Features

- **Multi-parameter filters** — Policy Year, Beneficiary District, Hospital Name/Type, Package Specialty, TPA, Identity Status, and Claim Status
- **Monthly Claims Trend** — line chart of claim volume by month (based on TID created date)
- **Top 10 Hospitals by Claim Amount** — ranked bar chart
- **Claims by Beneficiary District (Top 10)** — ranked bar chart
- **Claims by Hospital Type** — donut chart (Private, Government, Trust, Others)
- **Claims by Policy Year** — bar chart, 2018–2022
- **Top Package Specialties by Claim Amount** — ranked bar chart
- **TPA-wise Approved Amount (Top 5)** — ranked bar chart
- **Claims by Rejection Reason** — donut chart
- **Top 10 Beneficiaries by Claim Amount** — detailed table with member ID, name, district, and claim amount

## 🛠️ Tools Used

- **Tableau** — dashboard design & visualization
- **Excel / CSV** — source data preparation

## 📁 Repository Structure

```
├── README.md
├── dashboard.twbx          # Tableau packaged workbook (add your file here)
└── data/
    └── claims_data.csv     # source dataset (add your file here)
```

## 📈 Key Insights

- Private hospitals account for the majority of claims (55.73%), followed by Government (26.99%) and Trust (12.20%).
- R.K. Hospital leads all hospitals in claim amount (₹9.02 Cr), closely followed by Nayati Hospitals Ltd. and D.K.S.N. Hospital (both ₹6.98 Cr).
- Patna is the top-claiming district (₹18.76 Cr), well ahead of Nalanda and Gaya.
- Claims peaked sharply in 2021 (17,255 claims) after steady year-over-year growth from 2018, before declining in 2022.
- General Surgery is the highest-value package specialty (₹28.37 Cr), followed by Orthopaedics (₹26.81 Cr).
- Medi Assist India TPA Pvt. Ltd. has the highest approved amount among TPAs (₹62.36 Cr).
- "Documentation Missing" is the leading rejection reason, accounting for 20.43% of rejected claims.
