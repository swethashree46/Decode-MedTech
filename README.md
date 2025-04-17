

##  **README.md**

### **Project Title:**
**DecodeHealthTech**  
*Decoding the Evolution and Impact of Healthcare Technologies*

---

### **Overview**
This project provides a data-driven interface to explore, analyze, and summarize the evolution and impact of healthcare technologies over time. By connecting to a healthcare tech database, the script enables users to:
- View all healthcare technologies stored in the database.
- Filter technologies by impact area.
- Analyze employment impact and success rates.
- Explore technologies introduced in a specific year (2023–2025).
- Look up the success status of a particular technology.

---

### **Key Features**
- **Interactive Filtering:** Search by impact area (e.g., *Patient Care*, *Data Security*) to analyze trends.
- **Employment Analysis:** Identify whether technologies increased, decreased, or had a neutral impact on employment.
- **Year-Based Insights:** Explore technology innovations by year and their success impact.
- **Success Lookup:** Query individual technologies for success/failure classification.

---

### **Tech Stack**
- **Python**  
- **pymysql** (for MySQL database connection)  
- **pandas** & **numpy** (for data analysis)

---

### **Database Requirements**
Ensure you have a MySQL database named `healthcare_tech_db` with a table called `technology` containing the following columns:
- `tech_name`  
- `impact_area`  
- `employment_impact` (`increased`, `decreased`, `neutral`)  
- `success_status` (`success`, `failure`)  
- `year` *(optional, for year-specific queries)*

---

### **Example Analysis Output**
```bash
Enter an impact area to filter (e.g., 'Patient Care', 'Data security', etc.): Patient Care

Analysis Summary:
Total Technologies: 7
Increased Employment: 4
Decreased Employment: 2
Neutral Employment: 1
Success Rate (%): 71.43

---


