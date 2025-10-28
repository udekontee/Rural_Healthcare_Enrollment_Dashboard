# Rural_Healthcare_Enrollment_Dashboard
  **Data Source: CMS – Cleaned in MySQL, Visualized in Power BI**
  
  ## 📊 Project Overview
This Power BI project visualizes national **Rural Health Clinic (RHC)** enrollments to reveal how healthcare access varies across U.S. states.  
The dataset from the **Centers for Medicare & Medicaid Services (CMS)** was cleaned and transformed using **MySQL**, then visualized in **Power BI** to explore clinic growth, incorporation rates, and demographic coverage.
The dashboard provides data-driven insights into:
- Total clinic enrollments nationwide  
- State-level participation in rural health programs  
- Long-term enrollment trends and growth patterns  
- Top states driving healthcare access expansion  

  ## 🎯 Project Objectives
- Identify states with the **highest and lowest enrollment participation**  
- Measure **average enrollments per state** and **total incorporation rates**  
- Track **enrollment growth over time** using historical data  
- Create **interactive KPIs and slicers** for flexible data exploration  

  ## ⚙️ Tools & Technologies
| Category | Tools Used |
|-----------|-------------|
| Data Preparation | MySQL, Excel |
| Data Visualization | Power BI |
| Data Cleaning | SQL queries, normalization |
| Documentation | Markdown (GitHub README), Excel metadata tracking |

  ## 🧩 Workflow Overview
1. **Data Extraction:** Retrieved CMS enrollment data in CSV format.  
2. **Data Cleaning:** Removed duplicates, handled missing values, and standardized state codes in **MySQL**.  
3. **Data Modeling:** Created fact and dimension tables for clinic counts and incorporation metrics.  
4. **Dashboard Design:** Built a Power BI dashboard featuring:
   - KPI Cards for Total Enrollments, States Represented, and Incorporation States  
   - Bar Chart for Clinics by State  
   - Donut Chart for Top 10 States by Enrollments  
   - Line Chart showing Enrollment Trends Over Time  
   - Interactive Slicers for State selection
     
# 📸 Dashboard Narratives
The dashboard provides a multi-angle view of rural healthcare access:
1) **Total Enrolled Clinics (3.723K)**
    - Displays the total number of active RHC enrollments nationwide.
    - A key KPI for evaluating program reach and scale.
2) **Total States Represented (45)**
    - Shows the extent of RHC enrollment across the country.
    - Indicates strong adoption of the RHC program, with a few remaining states yet to join.
3) **Total Incorporation States (47)**
    - Tracks the number of states that have formally incorporated RHC services.
    - A leading indicator of program compliance and infrastructure readiness.
4) **Clinics by State (Enrollment Distribution)**
    - A horizontal bar chart ranking states by total enrollments.
    - Kentucky (KY) leads with 347 clinics, followed by Tennessee (TN) and California (CA), highlighting regional concentration in the South.
5) **Top 10 States by Enrollments (Donut Chart)**
    - Provides a percentage breakdown of top-performing states in the program.
    - Useful for comparing proportional representation among states.
6) **Enrollment Trend Over Time (Line Chart)**
    - Depicts RHC growth since the 1900s, with major spikes in the late 1990s–2000s, reflecting federal healthcare expansion policies.
    - The gradual dip at the end indicates data stabilization or reporting lags.
7) **State Slicer (Right Panel)**
    - An interactive filter allowing users to view all visuals for a selected state.
    - Enables data-driven comparison between regions.
      
   # 💡 Key Insights
          - Over 3,700 clinics are currently enrolled across 45 states.
          - Kentucky, Tennessee, and California are the top 3 states in RHC participation.
          - The late 1990s–2000s saw the fastest growth in rural healthcare programs.
          - States with fewer enrollments may indicate rural access gaps or limited program adoption.
 # 🧠 Learning Outcomes
This project strengthened my ability to:
          - Transform real-world healthcare data into actionable visual insights.
          - Build interactive dashboards using Power BI slicers and DAX formulas.
          - Translate SQL-based analytics into clear performance indicators.
          - Design accessible, narrative-driven visual reports for decision-makers.
              
## 📸 Dashboard Preview
![Rural Health Clinics Enrollment Dashboard](PowerBI_Dashboard.png)
    <img width="873" height="499" alt="image" src="https://github.com/user-attachments/assets/fc8ece36-2777-4cc7-b53b-f3404362e04d" />

## 🧾 Project Files
| File | Description |
|------|--------------|
| `healthcare_enrollments.sql` | SQL queries used for cleaning and aggregating enrollment data |
| `healthcare_data.csv` | Processed dataset ready for visualization |
| `PowerBI_Dashboard.png` | Screenshot of the Power BI report |
| `README.md` | Project documentation |

## 🏥 Relevance to Healthcare & Data Roles
This project demonstrates:
  - **Attention to data accuracy** and quality control (aligned with data entry & validation roles).  
  - **Proficiency in Microsoft tools** (Power BI, Excel, SQL).  
  - **Healthcare data familiarity** through CMS enrollment analysis.  
  - **HIPAA awareness** and responsible data handling practices using public datasets. 

# 📚 Author
👩🏽‍💻 U Dekontee Kun
📬 Email: udekontee@gmail.com
🔗 Portfolio: github.com/udekontee

✅ Why This README Works
It ties exactly to your visuals:
        - Highlights your KPIs and slicers.
        - Explains your MySQL–Power BI workflow.
        - Positions you as a data storyteller — not just a dashboard maker.
