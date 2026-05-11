# NorthStar-Logistics-Analytics Assignment-CASE STUDY

This repository contains the end-to-end data audit, diagnostic engineering, and architectural redesign for **NorthStar Logistics**, a high-velocity urban mobility provider. 

## 📋 Project Overview
NorthStar faced a "Visibility Gap" due to fragmented data and system bottlenecks. This project solves these challenges through a three-phase integrated analytical approach.

---

## 📁 Repository Structure

### 1. Section 1: Relational Audit (SQL & R)
* **Objective:** Audit historical performance and identify location-based bottlenecks.
* **Tech Stack:** R, `sqldf`, `ggplot2`.
* **Key Focus:** Data normalization, median imputation for battery health, and complex multi-table joins to identify hub congestion (H05/H08) and high-value revenue risks.

### 2. Section 2: Diagnostic Engineering (Python)
* **Objective:** Diagnose "why" failures occur using advanced statistical modeling.
* **Tech Stack:** Python, `Pandas`, `NumPy`, `Seaborn`.
* **Key Focus:** KPI engineering (Cost per KM, Profit Margin Index), Anomaly Detection using the IQR method, and multivariate diagnostic plots (Boxenplots, Faceted KDE).

### 3. Section 3: Cloud-Native NoSQL Implementation (MongoDB)
* **Objective:** Architect a scalable solution for high-velocity platform events.
* **Tech Stack:** MongoDB Atlas, `pymongo`, Python.
* **Key Focus:** Transitioning from flat tables to a **Multi-Layer Nested Document Structure**. Implementation of indexing strategies (IXSCAN) to optimize real-time query performance.

---

## 🚀 Key Insights & Findings
* **Operational Bottlenecks:** Identified that Hubs H05 and H08 were operating 35% beyond physical capacity.
* **Asset Risk:** Isolated specific battery degradation patterns in the e-bike fleet.
* **Performance Gains:** Improved query efficiency by implementing single-field and compound indexes in the NoSQL layer.
* **The "Loyalty Gap":** Discovered that high-loyalty customers have low app engagement, identifying a major revenue growth opportunity.

---

## 🛠️ Requirements & Setup
To run these notebooks, you will need:
* A Google Colab environment.
* A MongoDB Atlas Cluster (for Section 3).
* The following libraries: `sqldf`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `pymongo`, `certifi`.

## 🎓 Author
**PARVATHI RAMADAS** *Final Year Computer Science Student*
