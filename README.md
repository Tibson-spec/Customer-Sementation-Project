# **Work Order Backlog Management Dashboard**  
A Power BI dashboard providing actionable insights into work order backlog management using advanced data cleaning and transformation techniques with Power Query.  

---

## **Problem Statement**  
Managing work orders in large organizations comes with several challenges:  
- **Escalating backlogs**: Delays in work order execution due to uneven workload distribution.  
- **Resource bottlenecks**: Inefficient allocation of resources across departments.  
- **Prolonged durations**: Extended pending periods for critical work orders.  
- **Underutilized planned hours**: Discrepancies between planned and executed hours, resulting in operational inefficiencies.  

This project addresses these challenges with a data-driven solution to improve operational performance.  

---

## **Solution Overview**  
To tackle these issues, I developed a dynamic Power BI dashboard that:  
- Provides a centralized platform to monitor backlog metrics.  
- Offers actionable insights to optimize resource allocation and prioritize tasks.  
- Drives data-driven decision-making for backlog reduction.  

Explore the Power BI dashboard [here](./PowerBI/WorkOrderBacklog.pbix).  

---

## **Key Features**  

### **1. End-to-End Data Cleaning with Power Query**  
- **Data Transformation**:  
  - Removed duplicates, null values, and inconsistencies.  
  - Standardized date formats and merged datasets from multiple sources.  
- **New Column Additions**:  
  - Calculated backlog durations dynamically.  
  - Flagged overdue work orders (e.g., >50 days).  

### **2. Dashboard Visualizations**  
- **Comprehensive Overview**:  
  - Displays total backlog count, hours, and planned hours.  
- **Drill-Down Analysis**:  
  - Backlog distribution by duration (e.g., 5–10 days, 50+ days).  
  - Departmental contributions (e.g., Drilling, Maintenance, Engineering).  
  - Discipline-specific breakdown (e.g., Mechanical, Electrical, Subsea).  
- **Trend Analysis**:  
  - Monthly backlog trends to identify spikes and operational patterns.  
  - Planned vs. executed hours for monitoring resource utilization.  

### **3. Insights and Recommendations**  
- High-backlog areas identified in Integrity and Maintenance departments.  
- Long-duration backlogs (>50 days) flagged for immediate action.  
- Underutilized planned hours optimized through better resource alignment.  

---

## **Screenshots**  
### **Dashboard Overview**  
![Dashboard Overview](./Screenshots/DashboardOverview.png)  

### **Drill-Down Analysis**  
![Drill-Down Analysis](./Screenshots/DrilldownAnalysis.png)  

### **Trend Analysis**  
![Trend Analysis](./Screenshots/TrendAnalysis.png)  

---

## **Results Achieved**  
- **Reduced Backlogs**: Prioritized high-duration backlogs for faster resolution.  
- **Optimized Resource Utilization**: Balanced workloads across departments.  
- **Improved Decision-Making**: Enabled data-driven resource planning.  
- **Enhanced Operational Visibility**: Provided a real-time centralized view of work order performance.  

---

## **How to Run the Project**  
1. Clone this repository.  
2. Download raw datasets from the `Data/RawData` folder.  
3. Open the Power BI file `WorkOrderBacklog.pbix` using Power BI Desktop.  
4. Load the datasets and review the dashboard to interact with filters and visualizations.  

---

## **Acknowledgements**  
This project was inspired by real-world operational challenges in work order management. Special thanks to my collaborators for their feedback and support during the development process.  

---

Feel free to reach out for further discussions or collaboration opportunities!  

[Visit My Portfolio](#) | [Connect on LinkedIn](#)  

---

Let me know if you’d like further refinements or additions!
