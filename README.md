# NYC Parking Violations Analysis

## Project Overview

This project analyzes parking violations issued in New York City from 2017 to 2020. The purpose of the project is to identify patterns in parking violations, including the most common violation types, the streets with the highest number of violations, and the times and days when violations occur most often.

The analysis was completed using Python, Pandas, and Matplotlib.

## Project Goal

The main goal of this project is to answer the following question:

**When, where, and what types of parking violations occur most often in New York City?**

## Research Questions

This project focuses on four main questions:

1. What are the most common parking violation types?
2. Which streets have the highest number of parking violations?
3. What time of day are parking violations most common?
4. Which days of the week have the most parking violations?

## Dataset

The dataset used in this project comes from NYC Open Data and contains parking violation records for New York City.

The dataset includes information such as:

- Issue date
- Violation code
- Violation description
- Vehicle information
- Violation time
- Violation county
- Street name
- Fine amount

Due to file size, the raw dataset is not included in this repository. The data can be downloaded from NYC Open Data by searching for **Parking Violations Issued**.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- GitHub

## Key Findings

### 1. Most Common Parking Violations

The most common violation was **photo school zone speed violation**. Other frequent violations included **failure to stop at a red light**, **expired muni meter**, and **bus lane violation**.

### 2. Streets with the Most Parking Violations

The streets with the highest number of violations included **EB Horace Harding Expressway**, **WB Goethals Road**, and **Horace Harding Expressway**.

### 3. Parking Violations by Time of Day

Parking violations were most common during daytime hours, especially between approximately **10 AM and 3 PM**.

### 4. Parking Violations by Day of Week

Violations were highest during weekdays, especially in the middle of the week. Weekend violations were much lower compared to weekdays.

## Conclusion

This analysis shows that parking violations in New York City are concentrated around specific violation types, locations, and times. Violations were most common during weekday daytime hours, which may be connected to higher traffic levels, increased parking demand, and active enforcement during workday hours.

These findings suggest that drivers should be especially careful when parking during weekday daytime hours and on streets with a high number of recorded violations.
## Project Files

```text
parking-violations-analysis/
│
├── README.md
├── parking_violations_analysis.ipynb
├── requirements.txt
│
├── images/
│   ├── top_violations.png
│   ├── top_streets.png
│   ├── violations_by_hour.png
│   └── violations_by_day.png
│
└── data/
    └── README.md



This analysis shows that parking violations in New York City are concentrated around specific violation types, locations, and times. Violations were most common during weekday daytime hours, which may be connected to higher traffic levels, increased parking demand, and active enforcement during workday hours.

These findings suggest that drivers should be especially careful when parking during weekday daytime hours and on streets with a high number of recorded violations.
