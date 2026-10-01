# E-Commerce Fraud Transaction Analysis

## Project Overview
Analysis of over 1 million e-commerce transactions (Jan-Mar 2024) to find **where, when and from whom fraud happens**. The data was cleaned and transformed in Python, then modelled and visualised in a 2-page Power BI dashboard.

## Key Metrics
| Metric | Value |
|---|---|
| Fraud rate | 5.01% |
| Fraud amount | 40.10M |
| Total transaction amount | 330.73M |

Fraud makes up about 5% of transactions but about 12% of total transaction value, so fraudulent transactions tend to be higher in value.

## Key Findings
1. **Night-time is the riskiest period.** The fraud rate is about 10.5% between midnight and 5 AM, compared with about 3% for the rest of the day.
2. **New accounts carry the highest risk.** The fraud rate for the "New" age group is 22.36%, versus 3.00-3.94% for all other groups. New accounts account for 33K fraud cases and 17.7M in fraud amount.
3. **New and Established accounts drive most of the losses.** Together they make up about 86% of the total fraud amount (34.4M of 40.10M).
4. **Device and product category are weak indicators.** Fraud rates are nearly identical across mobile (5.06%), tablet (4.99%) and desktop (4.99%), and across product categories (about 4.96-5.05%).
5. **Fraud is stable over time.** The daily fraud rate stays between about 4.6% and 5.3% from January to March 2024, with no major spikes.

## Dashboard
**Page 1: Executive Overview**

![Executive Overview](Screenshots/page1%20report.png)

**Page 2: Fraud Analysis**

![Fraud Analysis](Screenshots/Page%202%20report.png)

The full dashboard export is available as a PDF: [Report/Fraudulent ecommerce report.pdf](Report/Fraudulent%20ecommerce%20report.pdf)

## Tools Used
- **Python:** data cleaning and transformation
- **Power BI:** data modelling (Transaction table with Customer, Date, Device, Payment and Product tables), measures (DAX) and dashboard design

## Repository Structure
- `data/raw data/` - sample of the raw transaction data
- `python/` - data cleaning notebook (`data cleaning.ipynb`) and transformation script (`data transform.py`)
- `Report/` - PDF export of the Power BI dashboard
- `Screenshots/` - dashboard page screenshots

## Dataset Note
The full raw file (374 MB) and the cleaned dataset (395 MB) are above GitHub's 100 MB file limit, so they are not included in this repository.
Dataset source: [add link here]

## Author
[Your name] | [LinkedIn profile link]
