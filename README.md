# PROJECT-EVALUATION-DASHBOARD-POWER-BI

*A comprehensive analytical solution for evaluating departmental performance, budget utilization, and project financial efficiency.*

---

## 📑 Table of Contents  
1. [Executive Summary](#-executive-summary)  
2. [Dashboard Preview](#-dashboard-preview)  
3. [Key Objectives](#-key-objectives)  
4. [Dashboard Overview](#-dashboard-overview)   
5. [Insights](#-key-insights)  
6. [Strategic Recommendations](#-strategic-recommendations)  
7. [Technical Implementation](#-technical-implementation)  
8. [Repository Structure](#-repository-structure)  
9. [Skills Demonstrated](#skills-demonstrated)  
10. [Contact](#contact)

---

## 📌 Executive Summary  
The **Project Evaluation Dashboard** provides a 360-degree view of departmental project performance, capital allocation, salary cost distribution, and project-level budget utilization.  

Developed in **Power BI**, the dashboard equips department heads, HR managers, and PMOs with critical insights needed to:

- Track capital investment vs. project outcomes  
- Benchmark departmental project cost efficiency  
- Identify cost overruns and underutilized budgets  
- Evaluate resource distribution and employee salary exposure  
- Align departmental goals with financial constraints  

This solution is built for **data-driven project governance and workforce planning**.

---

## 🖼 Dashboard Preview  
<img width="877" height="491" alt="HR Analysis" src="https://github.com/user-attachments/assets/daa54c13-4187-42e1-86ed-1b106d1c1271" />


---

## 🎯 Key Objectives  
- Provide transparency into **project funding, cost allocation, and salary impact**  
- Enable performance comparison across departments  
- Improve decision-making for budgeting and project prioritization  
- Enhance HR’s role in workforce cost management  
- Support strategic capital planning  

---

# 📊 Dashboard Overview  

## **Capital Overview**
- **Total Capital:** **$2.43M**  
- Capital allocated across 5 departments based on department goals and project priorities  
- Quickly highlights areas with highest financial exposure  

---

## **Department-Level Cost Analysis**
Key metrics visualized:

- **Project Cost** by Department — *Total: $570K*  
- **Salary Cost** by Department — *Total: $796K*  
- Capital vs. Budget vs. Actual Cost  
- Department goals for alignment with business strategy  

**Distribution Snapshot:**

| Department        | Capital | Budget | Project Cost | Salary Cost |
|------------------|---------|--------|--------------|-------------|
| Engineering      | $990K   | $2.4M  | $110K        | $160K       |
| Marketing        | $599K   | $1.6M  | $115K        | $158K       |
| Sales            | $416K   | $900K  | $90K         | $151K       |
| IT               | $238K   | $900K  | $90K         | $160K       |
| Human Resources  | $185K   | $1.1M  | $115K        | $167K       |

---

## **Employee Profile Panel**
Displays:

- Employee ID  
- Full name  
- Job title  
- HR manager  
- Department  
- Salary  

Used primarily for HR/managerial analysis when filtering by employee attributes.

---

## **Project Budget Analysis**
Includes:

- **Project Budget by Project Name**  
- **Project Budget by Department**  
- Comparison of actuals vs. allocated funding  
- Highlights capital-efficient vs. capital-intensive projects  

---

# 🔍 Key Insights  

## **Executive-Level Insights**
### **1. HR has the Highest Salary Cost ($167K)**  
Despite not being a revenue-generating unit, HR accounts for the **largest salary expense**, indicating:  
- Wide HR role coverage  
- Possibly senior staff concentration  
- Potential overstaffing risk  

### **2. Engineering Receives the Highest Capital Allocation ($990K)**  
Engineering is heavily funded relative to others, suggesting:  
- Innovation-driven strategy  
- Product development dependence  
- Long-term R&D investment  

### **3. Marketing Receives the Second-Highest Capital and Shows High Budget Needs**  
- High spending aligns with **brand awareness initiatives**  
- Cost levels justify performance monitoring to ensure ROI  

### **4. IT Has Lower Capital Allocation But High Salary Expense**  
- IT salaries ($160K) are disproportionately high relative to capital ($238K)  
- Indicates more human-resource driven operations (support, development, security)  

---

## **Department Insights**

### **Engineering**
- Highest capital allocation ($990K)  
- Moderate project and salary costs  
- Strategic focus on **product and innovation**  
- Cost-effective in project execution  

### **Marketing**
- High capital and budget requirements  
- Highest overall cost-to-budget ratio  
- Must be closely aligned with revenue impact  

### **Sales**
- Lower capital allocation ($416K) compared to operational dependency  
- Efficient cost usage—project cost is lowest among departments  
- Opportunity for increased investment to support revenue activities  

### **IT**
- High salary cost relative to project cost  
- Underfunded compared to operational importance  
- Possible risk of technology backlog or delayed innovation  

### **Human Resources**
- Salary-heavy department  
- High project cost relative to capital  
- Opportunity for HR process automation to reduce cost burden  

---
<img width="973" height="503" alt="HR Analysis 2" src="https://github.com/user-attachments/assets/9f3fdd09-28d9-40f7-b4e1-1366aff3c90b" />

## **Project Insights**

### **Top Budget Consumer Projects**
- Product Launch  
- Brand Repositioning  
- Mobile App Development  

### **Project Cost Efficiency**
- Some projects consume high capital but low project output  
- Engineering and Marketing projects show the most balanced capital-to-output ratio  
- IT projects are low-cost but may be constrained by limited capital  

### **Underfunded Strategic Areas**
- Customer Support Systems  
- CRM Integration  
These lower-budget projects are typically foundational for organizational efficiency.

---

# 🧠 Strategic Recommendations  

## **1. Reallocate Capital for Cost-Intensive Departments**
- HR and IT salary load should be balanced with automation and process optimization  
- Increase Sales and IT capital allocation to strengthen revenue and operational support  

## **2. Strengthen ROI Tracking for Marketing & HR Projects**
- Implement KPI-based evaluation metrics tied directly to revenue or employee engagement impact  

## **3. Introduce Workforce Cost Optimization**
- Review salary structures in HR and IT for efficiency  
- Consider outsourcing or hybrid staff models  

## **4. Prioritize Engineering Projects with High Strategic Impact**
- Engineering shows strong cost-efficiency → increase funding for high-growth potential projects  

## **5. Improve Project Budget Governance**
- Standardize project budgeting rules  
- Introduce centralized cost control mechanisms  
- Conduct quarterly budget-to-actual variance analysis  

## **6. Enhance IT Funding to Reduce Operational Risks**
- IT is underfunded compared to organizational dependency  
- Increase investment in infrastructure, cybersecurity, and internal systems  

---

# 🛠 Technical Implementation  

## Tools & Technologies
- **Power BI Desktop** – DAX calculations, visuals, KPIs  
- **Power Query** – ETL and data transformation  
- **DAX Measures** – capital, cost, and ROI metrics  
- **Star Schema Data Modeling**  

---

## Data Model Design

### **Fact Tables**
- Fact_ProjectCost  
- Fact_SalaryCost  
- Fact_Budget  
- Fact_Capital  

### **Dimension Tables**
- Dim_Department  
- Dim_Project  
- Dim_Employee  
- Dim_Status  

This structure optimizes performance for slicing by department, employee, project, and status.

---

## Skills Demonstrated

- **Advanced Power BI Dashboard Development**  
  Designed an interactive, multi-page analytical dashboard with dynamic slicers, KPI cards, and drill-through insights tailored for healthcare operations.

- **DAX and Data Modeling Expertise**  
  Developed complex DAX measures, calculated tables, and custom time-intelligence logic to support accurate patient waitlist analytics and historical comparisons.

- **Power Query Transformation Workflows**  
  Cleaned, reshaped, merged, and standardized diverse datasets using Power Query M-language to ensure data integrity and optimal refresh performance.

- **Fact/Dimension Schema Design**  
  Implemented a robust star-schema model to separate facts from dimensions, enabling efficient aggregation, slicing, and filtering across multiple performance metrics.

- **Performance Optimization**  
  Applied best practices, including column reduction, measure optimization, and relationship tuning to enhance dashboard responsiveness and minimize resource consumption.

- **Data Analysis, Healthcare KPIs, and Reporting**  
  Translated raw health service data into interpretable metrics such as ALOS, GMLOS, waitlist trends, specialty-level KPIs, age-band insights, and multi-year backlog patterns.

- **Storytelling for Executive Decision-Making**  
  Synthesized complex operational data into clear, actionable insights for senior leaders, ensuring the dashboard supports strategic planning, capacity management, and policy decisions.

---

## Contact

**Name:** Dike Nnaemeka Destine  
**Role:** Data Analyst | BI Developer | Instructor  

**GitHub:**  
[https://github.com/Destinetheanalyst](https://github.com/Destinetheanalyst)

**LinkedIn:**  
[https://www.linkedin.com/in/nnaemeka-destine-dike-9a27b531a](https://www.linkedin.com/in/nnaemeka-destine-dike-9a27b531a)

