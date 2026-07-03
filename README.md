# Hotel Booking Demand Analysis 🏨📊

A comprehensive, data-driven analysis of hotel booking datasets using Python. This project uncovers structural booking behavior, cancellation demographics, seasonal demand, and customer segmentation to optimize hospitality revenue and resource management.

---

## 📌 Features & Analysis Workflow

### 1. Comprehensive Data Exploration (EDA)
* Loaded and profiled the core dataset (`hotel_bookings.csv`) leveraging Pandas capabilities.
* Analyzed distribution properties, checked structural data alignments, and evaluated customer distributions across different hotel types (Resort Hotels vs. City Hotels).

### 2. Feature Engineering (Tailored Customer Profiling)
Created strategic new metrics to capture explicit booking context and answer business questions:
* **`total_guests`:** Aggregated counts of adults, children, and babies to establish total capacity per room reservation.
* **`traveler_type`:** Built a custom mapper function to segment reservations into structured consumer categories: `Single`, `Couple`, or `Family/Group`.

### 3. Data Visualization & Insights (`seaborn` & `matplotlib`)
* **Demand Fluctuation:** Visualized seasonal trends to isolate peak booking months and optimize pricing strategies.
* **Cancellation Analysis:** Investigated the primary drivers behind high cancellation frequencies across different market segments.
* **Traveler Demographics:** Generated insights demonstrating which group profiles (Families vs. Individuals) generate longer stays and higher average daily rates (ADR).

---

## 🛠️ Technical Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib

---

## 📄 Project Context & Details
* **Institution:** University College of Applied Sciences (UCAS).
* **Course:** Data Analysis & Visulizations.
* **Developer:** Amal Ahmed Abu Elba
* **Core File:** Interactive code workbook available in [`HotelBookingDemand.ipynb`](./HotelBookingDemand.ipynb)
