# Elder Scrolls Online: Furnishing Plan Materials


### __Introduction__

For my Data Analysis 2 project, I'm analyzing the demand for materials needed to craft new furnishing plans added in major content patches for *The Elder Scrolls Online*. 




__Objective:__ assess how furnishing plans added in past major content patches would likely affect demand for crafting materials in The Elder Scrolls Online.



---

## Setup

### __Requirements:__

Python 3.10.4

__Packages used:__

- jupyter notebook
- pandas 1.4.4
- requests 2.28.1
- beautifulSoup4 4.11.1
- matplotlib 3.5.2
- ipykernel

------ *add conda instructions* -----

------ *add tsv instructions* -----

---


## Data Sources

- Tsu's Magical Pricing Assistant [link](https://docs.google.com/spreadsheets/d/1gA3gLV_trvozQjHANvCWIrzmCMhEGdf6dm7N_U2CYuY/)

- ESO Furnishings Helper by Sapphire_Ocelot [link](https://docs.google.com/spreadsheets/d/11XxNt07znE3cHqWMecO-NxSjNWWnaA8hMA6uDV_53O8/)

- The Unofficial Elder Scrolls Pages (new plan lists) [UESP.net](https://en.uesp.net/wiki/Main_Page)

- ESO-Hub.com (new plan details) [ESO-Hub.com](https://eso-hub.com/en/housing)


---


## Project Plan


__Feature 1: Loading data.__

Read three spreadsheets from Google Sheets, and scrape data from UESP.net and ESO-HUB.com to get a list of newly added furnishing plans and fill out the data for each.

__Feature 2: Clean and operate on the data while combining them.__ 

Merge the patch data from ESO Furnishings Helper with the plan materials in Tsu's Magical Pricing Assistant. 

Remove any duplicate plans, and use pandas concatenate to combine with web scraped plan data.

Find the sum of housing materials required to craft each plan and the total plans added per content patch, and merge with the patch information dataframe.

__Feature 3: Visualize / present your data.__ 

Create three figures with matplotlib: 

- a horizontal bar graph of the number of plans released per update 
- pie charts for the ratio of housing materials required to craft plans added in each update 
- a bar graph of plans added over time

__Feature 4: Best practices.__ 

Use a conda environment and included instructions for setup.

---

__Changes to Project Plan:__

*Original project plan was to analyze Tales of Tribute card game matches.*

*Changed project to ESO Furnishing Plan Materials to build on Data 1 project topic.*








