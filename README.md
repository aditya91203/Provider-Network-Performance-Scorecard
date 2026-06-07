# Provider Network Intelligence Dashboard
### Medicare Fee-for-Service Analysis | Tableau | CMS Open Data

## Overview
An interactive Tableau dashboard benchmarking US Medicare providers 
across quality, cost, and network adequacy — identifying high-value 
providers, specialty coverage gaps, and geographic performance 
patterns using publicly available CMS data.


## Business Question
Which providers deliver the best patient outcomes at the lowest cost, 
and where are the network coverage gaps across the US?

## Data Sources
| Dataset | Source |
|---|---|
| Medicare Physician & Other Practitioners | CMS.gov |
| Unplanned Hospital Visits | CMS Provider Data Catalog |
| Complications & Deaths | CMS Provider Data Catalog |

## Dashboard Pages
1. Network Overview Map — provider density by state and specialty
2. Quality Scatter Plot — cost vs. quality quadrant analysis
3. Provider Drill-Through — measure-level hospital performance
4. Specialty Cost Benchmarking — avg payment by specialty vs. national avg
5. State Heatmap — quality measure performance across all 50 states

## Key Metrics
- Average Payment per Service
- Quality Tier (High / Average / At Risk)
- Charge to Payment Ratio
- Provider Volume Tier

## Files
- `Project3_Dashboard.twbx` — Tableau packaged workbook
- `Project3_Dashboard_Documentation.docx` — Full project documentation
- `Project3_Column_and_Sheet_Reference.docx` — Column & sheet reference guide
- `/data/` — Cleaned CSV files used in the dashboard

## Tools Used
Tableau Desktop | Microsoft Excel | CMS Open Data
