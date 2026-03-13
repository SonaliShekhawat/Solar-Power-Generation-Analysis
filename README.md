# Solar-Power-Generation-Analysis

## Overview
This project provides a comprehensive analysis of solar power generation data, showcasing performance metrics, temporal trends, and comparisons across different installation types using Power BI.

## Data Source
- **Source**: Kaggle
- **Dataset**: al-pv-2006 solar.xlsx (located in Raw Data/ folder)

## Methodology
- **Data Cleaning**: Performed using Power BI/Power Query Editor
- **Analysis Tool**: Power BI Desktop

## Key Findings

### Executive Summary (Key Performance Indicators)
- **Max Capacity**: 80 MW
- **Max Power Generated**: 74.60 MW
- **Total Power Generated**: 7.69M MW
- **Average Power Generated**: 7.33 MW

### Temporal Production Trends
- **Monthly Performance**: Power generation increases from December (lowest: ~0.50M MW) to May (highest: ~0.80M MW), showing seasonal correlation with daylight hours
- **Daily Patterns**: Fluctuates between 0.14M MW and 0.32M MW, with peaks around days 10 and 25
- **Hourly Distribution**: Follows a bell curve, starting around hour 6, peaking at ~25 MW at hour 13 (1 PM), and ending around hour 20 (8 PM)

### Performance by Site Type
- **UPY (Utility-Scale Photovoltaics)**:
  - Average Capacity: 66.67 MW
  - Average Power Generation: 11 MW
- **DPV (Distributed Photovoltaics)**:
  - Average Capacity: 36.85 MW
  - Average Power Generation: 6 MW

UPY sites demonstrate significantly higher capacity and output, serving as the primary drivers of total power generation.

## Project Structure
├── Clean Data/
│   └── al-pv-2006 solar.xlsx
├── Description/
│   └── Description.txt
├── LICENSE
├── Raw Data/
│   └── al-pv-2006 solar.xlsx
├── README.md
└── Result/
    ├── Solar Power Generation.pbix
    └── Solar Power Generation.png
---

