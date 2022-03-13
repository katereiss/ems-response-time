# Visualizing Cardiac Arrest Locations in NYC
### Abstract:

The Fire Department of New York (FDNY) is interested in improving their service to their community by identifying how to further reduce deaths due to cardiac arrest. From 2011 to 2017, FDNY responded to 54,073 deaths due to cardiac arrests. While many of these deaths cannot be prevented by FDNY actions, even a small improvement can save many lives. In these emergencies where seconds sometimes make a difference between life and death, it is worth exploring if there are features associated with cardiac arrest deaths so that some may be prevented.

### **Design:**

- Business Problem
    - How can FDNY reduce the number of preventable deaths?
- Solution paths:
    - Find relationships between deaths due to cardiac arrest and features such as response time and incident location.
- Impact hypothesis
    - Identifying features that are associated with cardiac arrest deaths will help identify actions that will decrease preventable deaths. We will use cardiac arrest data to reduce the number of preventable deaths.
- Measures of success:
    - The percentage of deaths due to cardiac arrest decreases after actions are implemented.
- Risks and assumptions:
    - Risk: Data on patient condition after hospital care is not present in this dataset.
    - Assumption: There are some deaths that can be prevented with FDNY interventions.

### **Data:**

- I used a large dataset of all FDNY EMS incidents in a six-year timeframe. For analysis in Google Sheets, I made datasets of 74,000 cardiac arrests that were transported and 54,000 cardiac arrests that were pronounced dead.
- Dataset: [EMS Incident Dispatch Data]([https://data.cityofnewyork.us/Public-Safety/EMS-Incident-Dispatch-Data/76xm-jjuj](https://data.cityofnewyork.us/Public-Safety/EMS-Incident-Dispatch-Data/76xm-jjuj)) from NYC OpenData is a CSV dataset with 29 million rows where one row is one EMS incident. Some of the 31 columns include incident datetime, call type, response time in seconds, and zip code.

### **Algorithms:**

- I performed a thorough exploratory data analysis including cleaning and aggregation in Google Sheets. Tableau was used to explore and visualize the data to address the client's problem.

### **Tools:**

- Google Sheets
- Tableau
- Python for extracting cardiac arrest data from all EMS data

### **Communication:**

- Slides accompanying the 5-minute presentation delivered are attached as a pdf to this repo.
