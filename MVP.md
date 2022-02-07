The goal of this project is to deliver a well-scoped project proposal and preliminary analysis to the New York Fire Department (NYFD) with the goal of decreasing deaths due to cardiac arrest in their response area.

I used a large dataset of all NYFD EMS incidents in a five-year timeframe. For analysis in Google Sheets, I made datasets of 74,000 cardiac arrests that were transported and 54,000 cardiac arrests that were pronounced dead.

- Backstory
    - In 2015, the NYFD responded to 8,508 deaths due to cardiac arrests. From 2011 to 2016, cardiac arrests were responsible for 87% of NYFD incidents where the patient was pronounced dead.
- Business Problem
    - How can NYFD reduce the number of preventable deaths?
- Solution paths:
    - Find relationships between deaths due to cardiac arrest and features such as response time, incident location, and on-scene time.
- Impact hypothesis
    - Identifying features that are associated with cardiac arrest deaths will help identify actions that will decrease preventable deaths. We will use cardiac arrest data to reduce the number of preventable deaths.
- Measures of success:
    - The percentage of deaths due to cardiac arrest decreases after actions are implemented.
- Risks and assumptions:
    - Risk: Data on patient condition after hospital care is not present in this dataset.
    - Assumption: There are some deaths that can be prevented with NYFD interventions.
- Preliminary Analysis
    - The map below shows the zip codes in the NYFD response area with darker colors representing more deaths. This map suggests that further analysis on the zip codes with disproportionately high numbers of deaths due to cardiac arrests will suggest future actions.
    <img width="548" alt="Screen Shot 2022-02-07 at 1 27 20 PM" src="https://user-images.githubusercontent.com/84412675/152886365-c02eb7bd-66d8-46fa-8b89-545052cf1af7.png">

    
- Further questions:
    - How many NYFD stations are there in the zip codes with higher death counts?
    - How long is the average response time in these zip codes? Is it higher than the average response time for other zip codes?
    - Are there more EMS calls overall in zip codes with higher death counts?
