# Hungarian Gas Market Competition Analysis

Abstract and Results:
---

#todo (also see the documentation)

---
**Link Generation**: The script for generating links is not uploaded since it is enough that we only upload the results. The website was not consistent about its link generation, so we had to manually replace a lot of them. The output DataFrame is uploaded and it is called *gas_stations_with_links.csv*.

**Data Collecting and Cleaning**: The script is called *[HUN_Fuel1]data_collection_and_cleaning.ipynb*, and it needs the gas_stations_with_links.csv DataFrame. If you have everything installed you can run the whole script and after 4-5 hours you have your clean data. The competitons dataframe is also needed and uploaded so you can connect the freshly scraped data with competitions.

**Generating competition and external attributes**: In *[HUN_Fuel2]competition_generator.ipynb* we created the competition of the gas stations based on the city and radius. The output is a *competitions.csv* which is going to be merged with the dataframe, and the main output is: *gas_stations_{m}_{d}.csv* where m denotes month and d denotes the day.
