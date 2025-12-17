# Pharma-Market-Cannibalization-Analytics
Market cannibalization analysis of injectable anesthesia drugs using Medicare claims data. Evaluates competitive dynamics among four products, identifies causes of market share loss for Midazolam, and recommends data-driven strategies including territory targeting, HCP engagement, and predictive analytics.

## Table of Contents

* Project Overview
* Problem Statement
* Data Sources & Preprocessing
* Analysis & Key Insights

  1. Market Dynamics & Competitive Landscape
  2. Key Market Drivers
  3. Geographic Market Trends
* Strategies to Revitalize Product 2’s Market Share
* Project Deliverables
* Future Enhancements
* Repository Structure
* Contact Information

---

## Project Overview

This project presents an in-depth **market cannibalization analysis** within the **injectable anesthesia drug market**. The primary focus is to understand why **Product 2 (Midazolam Hydrochloride)** has failed to benefit from the declining market share of **Product 1 (Ketorolac Tromethamine)** and is instead losing share to **Product 3 (Fentanyl Citrate)**. By examining market behavior, competitive dynamics, and evolving drivers, the analysis delivers **actionable, data-driven recommendations** to improve Product 2’s market performance.

---

## Problem Statement

* **Product 1 (J1885 – Ketorolac Tromethamine):** Former market leader experiencing a steady decline in sales.
* **Product 2 (J2250 – Midazolam Hydrochloride):** Newly launched alternative intended to capture Product 1’s share, but currently underperforming.
* **Product 3 (J3010 – Fentanyl Citrate):** Rapidly expanding its market presence at the expense of Products 1 and 2.
* **Product 4 (J2704 – Propofol):** Emerging competitor showing early signs of adoption.

**Objective:** Analyze market dynamics and propose data-backed strategies to address the declining performance of Product 2.

---

## Data Sources & Preprocessing

The analysis integrates multiple datasets to build a comprehensive, analysis-ready dataset.

**Datasets Used:**

* **Medicare Claims Data:** ~1 million records containing procedure codes, diagnosis codes, and provider details
* **HCP Demographics Data:** Physician specialty and regional information
* **Patient Demographics Data:** Patient age groups and demographic attributes
* **Zip-to-Territory Mapping:** Links provider zip codes to sales territories
* **Diagnosis Code Mapping:** Maps ICD-10 codes to medical specialties
* **Procedure Code Mapping:** Associates HCPCS codes with specific products

**Data Preparation Steps:**

* Combined all claims sources into a single structured dataset (~28,368 records after filtering)
* Filtered for relevant procedure codes (J1885, J2250, J3010, J2704)
* Mapped diagnosis codes to specialties to analyze prescribing behavior
* Standardized geographic identifiers and linked them to sales territories
* Enriched claims with HCP and patient demographic details

---

## Analysis & Key Insights

### 1. Market Dynamics & Competitive Landscape

* **Product 3 (J3010)** outperforms Product 2 due to strong prescriber trust and engagement.
* **Product 1 (J1885)** continues to lose market share, signaling market saturation.
* **Product 2 (J2250)** lacks clear differentiation from competitors.

**Recommendations:**

* Leverage Product 1’s established brand equity to strengthen Product 2’s positioning
* Increase HCP engagement through education and incentive programs
* Improve territory-level targeting based on utilization and demographic trends

### 2. Key Market Drivers

**HCP & Patient Insights**

* Anesthesiologists and Cardiologists drive most prescriptions, with Product 3 leading adoption
* Patients aged **61–70** represent the highest claim volume

**Recommendations:**

* Expand educational outreach to key specialties
* Customize marketing initiatives for older patient populations

### 3. Geographic Market Trends

* Major metro areas (e.g., New York, NY; Los Angeles–San Diego, CA) show steep declines for Product 2
* Mid-sized territories (e.g., Phoenix, Minneapolis) present opportunities for recovery

**Recommendations:**

* Intensify efforts in high-density markets to regain share
* Deploy localized strategies in moderate-performing regions

---

## Strategies to Revitalize Product 2’s Market Share

* **Territory Optimization:** Increase field presence in the five weakest-performing regions
* **Co-pay & Payer Support:** Reduce financial barriers through patient assistance programs
* **Digital Engagement:** Use webinars, digital advertising, and targeted HCP outreach
* **Brand Repositioning:** Align Product 2 with Product 1’s trusted legacy
* **AI/ML Enablement:** Apply predictive analytics to improve targeting and marketing efficiency

---

## Project Deliverables

* **Jupyter Notebook (810 Final Python File.ipynb):** Data preparation, EDA, visualizations, and modeling
* **PowerPoint Presentation (BIA 810-D Final Presentation Group 5.pptx):** Executive summary of insights and recommendations
* **Original Data Files (CSV):** Source datasets (subject to privacy and compliance constraints)

---

## Future Enhancements

* Integrate private insurance claims for broader market coverage
* Develop advanced machine learning models to forecast prescribing behavior
* Conduct deeper competitive analysis on pricing and promotional strategies

---

## Repository Structure

```
Repository_Structure/
│
├── Original Data Files CSV/
│   ├── Medicare_Claims_data_part_1.csv
│   ├── Medicare_Claims_data_part_2.csv
│   ├── Medicare_Claims_data_part_3.csv
│   ├── Medicare_Claims_data_part_4.csv
│   ├── Medicare_Claims_data_part_5.csv
│   ├── HCP_demographics_data.csv
│   ├── Patient_demographics_data.csv
│   ├── Diagnosis_Code_Mapping.csv
│   ├── Procedure_Code_Mapping.csv
│   └── Zip_to_Territory_Mapping.csv
│
├── 810 Final Python File.ipynb
├── BIA 810-D Final Presentation Group 3.pptx
└── README.md
```

---

## Contact Information

For questions, feedback, or collaboration opportunities:

**Group 5 – BIA-810D**
GitHub: [https://github.com/OM6809](https://github.com/OM6809)
Email: **[orane@stevens.edu](mailto:orane@stevens.edu)**

---

Thank you for reviewing this market cannibalization analysis. We welcome feedback and collaboration opportunities.
