# Airport Authority Data Analysis

An interactive Power BI project for analyzing airline delays,
cancellations, on-time performance, and flight traffic patterns
between 2009 and 2011.

## 🔗 Interactive Power BI Dashboard

[View Power BI Dashboard](https://app.powerbi.com/reportEmbed?reportId=36e7b9e3-fa35-4e5e-813d-4e5109b5cd91&autoAuth=true&ctid=21d4f8bd-edd4-4342-a36c-6af608a51c80)

---

## 📌 Project Overview

This project analyzes airline flight data to understand patterns
in flight delays, cancellations, on-time performance, and airline
traffic.

The dashboard provides an interactive view of airline performance
across different years, months, days of the week, and origin airports.

---

## 🎯 Objectives

- Analyze on-time, delayed, and cancelled flights.
- Compare flight delays across different airlines.
- Analyze airline delay patterns across different years.
- Identify days of the week with higher flight activity.
- Identify months with higher flight traffic.
- Analyze airline traffic across origin airports.

---

## 📊 Dataset

The project uses an airline dataset containing flight activity
from 2009 to 2011.

### Key Fields

- Airline Name
- Origin Airport
- Departure Hour
- Day of Week
- Year
- Month
- On-Time
- Number of Flights
- Flights Delayed
- Flights Cancelled
- Avg Delay (min)

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and data visualization
- **Power Query** – Data cleaning and transformation
- **Microsoft Excel** – Source dataset

---

## 🔄 Data Preparation

The dataset was imported into Power BI and prepared using Power Query.

The main transformation steps included:

- Loading the airline dataset into Power Query.
- Reviewing column quality and distribution.
- Handling missing values in the average delay field.
- Correcting data types.
- Preparing the data for analysis.
- Loading the transformed dataset into Power BI.

---

## 📈 Dashboard

The Power BI report contains two analytical views.

### 1. Airport Authority Analysis

This dashboard analyzes:

- On-time, delayed, and cancelled flights
- Flight status by day of week
- Average delay by airline
- Airline delay trends across 2009, 2010, and 2011
- Overall accumulated average delay

### 2. Airline Traffic

This dashboard analyzes:

- Total flights by month
- Airline traffic
- Origin airport
- Day of week
- Year-wise traffic patterns

Interactive filters allow the analysis to be explored by
airline, airport, year, month, and day of week.

---

## 🔍 Key Findings

- Approximately **62% of flights were on-time**.
- Approximately **36% of flights were delayed**.
- Approximately **2% of flights were cancelled**.
- **Delta Air Lines Inc.** shows the highest accumulated average
  delay among the airlines displayed.
- The dashboard compares airline delay performance across
  **2009, 2010, and 2011**.
- **January** recorded the highest flight traffic among the
  months shown in the dashboard.
- The dashboard reports approximately **1.22M minutes** of
  accumulated average delay.

---

## 💡 Business Questions

The dashboard answers questions such as:

1. What percentage of flights are on-time, delayed, or cancelled?
2. Which airlines have higher flight delays?
3. How does airline delay performance vary by year?
4. Which days of the week have higher flight activity?
5. Which months have the highest flight traffic?
6. How does traffic vary across origin airports?

---

## 📂 Project Structure

```text
Airport-Authority-Data-Analysis/
│
├── Airline dataset.xlsx
├── airport authority analysis.pbix
├── airport authority analysis.pdf
└── README.md
