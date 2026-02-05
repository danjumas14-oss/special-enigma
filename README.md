# special-enigma
This repository contains two complete, end-to-end data analytics case studies focused on solving real business problems using data.  Each case study follows the full analytics workflow


---

## 🚚 Case Study 1: Logistics & Operations Analytics

### Business Objective
Improve delivery performance and reduce fuel costs by identifying operational inefficiencies across cities and vehicle types.

---

### Data Analysis Activities

**Data Preparation**
- Standardized date formats and delivery status labels
- Calculated delivery time (days) from order and delivery dates
- Created derived metrics: cost per kilometer, delivery delay flag

**Exploratory & KPI Analysis**
- Calculated overall on-time delivery rate
- Analyzed late deliveries by city and vehicle type
- Compared fuel cost efficiency across vehicle categories
- Identified high-cost, low-efficiency delivery routes

**SQL & Python Usage**
- SQL used to aggregate delivery performance by city and vehicle
- Python (pandas) used to validate KPIs and perform group-by analysis
- Cross-checked Excel and SQL results using Python

---

### Visualizations & Dashboards (Tableau)

The following visualizations were designed to support operational decision-making:

- **KPI Tiles**: On-time delivery %, average delivery time, cost per delivery
- **Bar Chart**: Late deliveries by city (to identify delay hotspots)
- **Bar Chart**: Late deliveries by vehicle type
- **Line Chart**: Monthly delivery volume trends
- **Scatter Plot**: Distance vs fuel cost to highlight inefficiencies

Each visualization includes filters for city, vehicle type, and time period.

---

### Key Insights
- Overall on-time delivery rate was approximately **71%**
- **Three cities accounted for over 40%** of late deliveries
- Trucks had the **highest cost per kilometer**
- Short-distance deliveries assigned to trucks significantly increased fuel costs

---

### Business Recommendations
- Reassign vehicles based on delivery distance
- Optimize routing in delay-prone cities
- Monitor city- and vehicle-level KPIs weekly

---

### Estimated Impact (Simulated)
- **18% reduction in late deliveries**
- **12% reduction in monthly fuel costs**

---

## 💰 Case Study 2: Sales & Business Performance Analytics

### Business Objective
Identify revenue drivers and growth opportunities by analyzing product performance, customer behavior, and regional sales trends.

---

### Data Analysis Activities

**Data Preparation**
- Removed cancelled and invalid transactions
- Standardized product and region categories
- Created monthly revenue and customer segmentation fields

**Exploratory & KPI Analysis**
- Calculated total revenue and average order value (AOV)
- Analyzed revenue contribution by product category
- Compared regional sales performance
- Evaluated new vs returning customer behavior

**SQL & Python Usage**
- SQL used to compute revenue aggregations and trends
- Python (pandas) used for product ranking and customer segmentation
- Results validated across tools to ensure accuracy

---

### Visualizations & Dashboards (Tableau)

The sales dashboard includes:

- **KPI Tiles**: Total revenue, AOV, % returning customers
- **Line Chart**: Monthly revenue trend
- **Bar Chart**: Revenue by product category
- **Bar Chart**: Revenue by region
- **Pie Chart**: Revenue split by customer type

Dashboards include interactive filters for region, product, customer type, and date.

---

### Key Insights
- **Top 20% of products generated over 60%** of total revenue
- Returning customers showed **higher AOV and total contribution**
- Some regions underperformed despite similar order volumes

---

### Business Recommendations
- Focus marketing spend on high-performing products
- Invest in customer retention strategies
- Reallocate resources from low-performing regions
- Align inventory planning with seasonal demand

---

### Estimated Impact (Simulated)
- **15% increase in revenue**
- **20% improvement in marketing efficiency**

---

## 👤 About Me

I am a data analyst focused on transforming raw data into **clear insights that support business decisions**. My work emphasizes practical analysis, clear visualization, and measurable business impact.

---

## 📬 Contact

📞 Phone: +2349048840226  
📍 Location: Nigeria  
🌍 Open to Remote & On-site Opportunities  

---

## ⭐ Notes for Reviewers

- Analysis logic is documented and reproducible
- Visualizations are designed for executive and operational audiences

Thank you for reviewing my portfolio.

