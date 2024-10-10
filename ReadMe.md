## Real-Time Micro Mobility(Bike) Analysis and Availability - Dashboard

**Project by:** [Rohith Raj Thalla](https://github.com/rohithrajthalla)  
**Dataset Source:** [Oslo Historical Data](https://oslobysykkel.no/en/open-data/historical), [Oslo Bysykkel GBFS API](https://gbfs.urbansharing.com/oslobysykkel.no/gbfs.json)  

---

### Overview

This project is focused on **analyzing and visualizing real-time bike availability** across bike-sharing stations in Oslo, Norway, using data from the **General Bikeshare Feed Specification (GBFS)** format. 

The project has two key components:
1. **Exploratory Data Analysis (EDA)**:  
   - Analyze bike-sharing data to understand patterns in station usage, bike distribution, and trends over time.
   - Identify top stations by bike activity, high-demand routes, and stations needing redistribution.
   - Perform clustering of stations based on availability and usage patterns to discover insights into user behavior.

2. **Real-Time Visualization Dashboard**:  
   - Build an interactive **real-time dashboard** using **Folium** to display bike availability across Oslo.
   - Highlight stations with low availability (fewer than 5 bikes) in **red** and others in **green**.
   - Auto-refresh the dashboard every 60 seconds to ensure the latest data is displayed.
   - Identify and list stations that require redistribution due to low bike availability.
   
### Goals:
- **Data Cleaning & Processing**: Ensure the dataset is cleaned and processed to handle issues like missing or erroneous data.
- **Exploratory Data Analysis**:
  - Visualize key metrics like the number of bikes available at various times of the day.
  - Perform **station ranking** based on usage, and identify trends in bike availability.
  - Use **clustering techniques** to segment stations based on user patterns and identify demand trends.
  
- **Real-Time Dashboard**: 
  - Display bike-sharing station locations with markers on a live map, updated every 60 seconds.
  - Highlight stations with low bike availability that require immediate redistribution.

- **Real-Time Map**
![Folium Map](Folium_Map.png)
