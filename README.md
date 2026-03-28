# 🏨 AtliQ Hotels – Hospitality Revenue Analytics Dashboard

---

## 📊 Live Dashboard

> 🔗 **[Click here to view the Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODNkNTMwZGMtYmExNS00YjdlLWI2MTUtNGU5NTM5NjI1ZDBjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

---

## 📌 Project Overview

AtliQ Hotels, a luxury hotel chain operating across multiple cities in India, was facing a significant decline in **market share and revenue**. The management decided to leverage **Business Intelligence and Data Analytics** to make data-driven decisions and regain their competitive edge.

This project involved building an end-to-end **Power BI analytical dashboard** for AtliQ Hotels' Revenue team to monitor key hospitality metrics, evaluate industry position, and deliver actionable insights.

---

## 🎯 Objective

- Analyze hotel performance across cities, room types, and booking platforms
- Track key revenue metrics such as RevPAR, ADR, Occupancy %, and DSRN
- Identify patterns in bookings, cancellations, and customer behavior
- Support the Revenue team in recovering lost market share and revenue

---

## 🗂️ Dataset Description

| File | Description |
|------|-------------|
| `dim_hotels.csv` | Hotel details including name, category, and city |
| `dim_rooms.csv` | Room type and class information |
| `dim_date.csv` | Date dimension with week, month, and day type |
| `fact_bookings.csv` | Transactional booking data with revenue, ratings, and status |
| `fact_aggregated_bookings.csv` | Aggregated bookings by property, room, and date |
| `metrics list.xlsx` | All calculated KPI metrics used in the dashboard |
| `Hospatality_Project.pdf` | Full project report and insights documentation |

---

## 📐 Key Metrics (KPIs)

| Metric | Full Form | Description |
|--------|-----------|-------------|
| **RevPAR** | Revenue Per Available Room | Core revenue efficiency metric |
| **ADR** | Average Daily Rate | Average revenue earned per booked room |
| **DSRN** | Daily Sellable Room Nights | Rooms available for sale per day |
| **DBRN** | Daily Booked Room Nights | Rooms booked per day on average |
| **DURN** | Daily Utilized Room Nights | Rooms actually used by guests |
| **Occupancy %** | | % of available rooms that were occupied |
| **Realization %** | | % of successful checkouts vs total bookings |

---

## 🔍 Key Insights

- 📉 AtliQ Hotels experienced consistent revenue loss in Luxury category properties
- 🏙️ Mumbai and Bangalore were the top-performing cities by RevPAR
- 📅 Weekend occupancy was significantly higher than weekday occupancy
- 🌐 Third-party booking platforms had higher cancellation rates vs direct bookings
- ⭐ Properties with lower customer ratings showed higher revenue decline

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard design and data visualization
- **Power Query** – Data cleaning and transformation
- **DAX (Data Analysis Expressions)** – Custom KPI and metric calculations
- **Microsoft Excel** – Metrics reference and data review
- **CSV Files** – Raw data source

---

## 📁 Project Structure

```
Hospatality/
│
├── 📄 README.md
├── 📊 Hospatality_Project.pdf
├── 📋 metrics list.xlsx
│
├── 🗃️ dim_date.csv
├── 🗃️ dim_hotels.csv
├── 🗃️ dim_rooms.csv
├── 🗃️ fact_bookings.csv
└── 🗃️ fact_aggregated_bookings.csv
```

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/rajanprasad3/Hospatality.git
   ```
2. Open the Power BI `.pbix` file (if available) in **Power BI Desktop**
3. Or view the **[Live Dashboard](#)** directly in your browser (no installation needed)
4. Refer to `Hospatality_Project.pdf` for full analysis and methodology

---

## 👤 Author

**Rajan Prasad**
📧 [GitHub Profile](https://github.com/rajanprasad3)

---

## 📃 License

This project is for **educational and portfolio purposes** only.

---

> ⭐ If you found this project helpful, consider giving it a star on GitHub!
