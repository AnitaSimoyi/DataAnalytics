Construction Data Analytics Portfolio
Project: Analyzing Estimated vs. Actual costs and material waste in structural design.
Goal: Using my 7+ years of engineering experience to drive data-informed decisions.
## 📊 Project Documentation: Cost Estimation Audit

### *Overview*
In this project, I performed a data integrity audit on a construction estimation dataset containing 1,000 project records. My goal was to verify if the automated estimates aligned with standard engineering cost-plus logic.

### *Data Dictionary*
* *Material_Cost:* Cost of raw materials (Steel, Timber, Concrete).
* *Labor_Cost:* Costs for site labor and fabrication.
* *Total_Estimate:* The final projected cost provided in the dataset.

### *Analysis Steps Taken*
1.  *Data Cleaning:* Converted raw CSV data into an Excel Workbook format to preserve analytical integrity.
2.  *Calculated Fields:* Added a Base_Cost column (Material + Labor) to establish a baseline for profit analysis.
3.  *Audit Formula:* Used =Total_Estimate - (Material_Cost + Labor_Cost) to isolate the hidden profit margin in each record.
4.  *Formatting:* Applied Excel Table formatting to allow for rapid filtering and sorting of high-value projects.
