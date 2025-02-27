---
# **Meteor Landings Analysis**
---
## **Table of Contents**
---

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

---
### **Project Overview**
---

Embarking on a journey through space and time, this project delves into NASA's extensive meteor impact dataset to uncover the hidden narratives of our cosmic visitors. By analyzing key variables—name, classification, mass, year, latitude, and longitude—we aim to visualize and understand the patterns and impacts of meteors that have collided with Earth.

Using Tableau's dynamic capabilities, we'll map out meteor landings across the globe, revealing geographical hotspots and temporal trends. Are certain regions more prone to meteor impacts? How have the frequency and magnitude of these celestial events changed over the years? By exploring these questions, we hope to shed light on the spatial and temporal distribution of meteorites, offering insights into both historical events and potential future patterns.

Each meteor isn't just a data point; it's a fragment of the universe with a unique story. From the colossal mass of the Hoba meteorite to the mysterious classification of others, we're tapping into the cosmic narrative that connects Earth to the vast expanse of space. By examining the mass and classification, we can delve into the origins and compositions of these meteors, enhancing our understanding of the materials that traverse our solar system.

This project isn't just about visualizing data—it's about bridging the gap between numbers and the awe-inspiring reality they represent. Through interactive charts and maps, we aim to make the information accessible and intriguing, inviting viewers to explore and discover the fascinating world of meteor impacts.

![Neteor Strike by Size](https://github.com/user-attachments/assets/9a7f7cdb-0d24-488e-be59-d52afa55d491)

![Meteor Strike Heat Map](https://github.com/user-attachments/assets/f692f867-c2de-49f0-8954-150ddbbf602d)


---
### **Data Sources**
---

This project draws upon the meticulously curated Meteorite Landings dataset provided by NASA, accessible at [NASA's Open Data Portal]( https://data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh/about_data).
The dataset serves as a comprehensive catalog of all known meteorite landings, encompassing a wide array of information that enables in-depth exploration and analysis. The key attributes extracted and utilized for this project include:
-	***Name***: The official designation of each meteorite, often reflecting the location near where it was found or observed.
-	***Classification***: Detailed typology of the meteorites, indicating their composition and group—such as iron, stony, or stony-iron—which provides insights into their origins and the processes that formed them.
-	***Mass***: Recorded in grams, this denotes the weight of the meteorite specimens, ranging from tiny micrometeorites to colossal masses that have significantly impacted the Earth's surface.
-	***Year***: The year when the meteorite was observed falling or when it was discovered, allowing for temporal analysis of meteorite events over centuries.
-	***Latitude and Longitude***: Geographical coordinates marking the precise location of each meteorite landing or find, crucial for spatial mapping and identifying potential patterns or clusters in meteorite distribution.

**About the Dataset**

NASA's Meteorite Landings dataset is part of their commitment to open data and transparency, providing researchers, educators, and enthusiasts with valuable scientific information. The dataset aggregates records from historical accounts, scientific observations, and verified discoveries, ensuring that each entry is authenticated and, where possible, enriched with detailed metadata.

The data is periodically updated to incorporate new findings and revisions, reflecting the dynamic nature of planetary science and ongoing exploration efforts. By leveraging this dataset, we tap into a wealth of knowledge that spans over a millennium of recorded meteorite events, capturing the fascinating intersection between our planet and extraterrestrial matter.

**Utilization in the Project**

For the purposes of this Tableau visualization project, the dataset serves as the foundation for:
-	***Spatial Analysis***: Mapping meteorite landings globally to identify geographic trends, impact hotspots, and regional variances in meteorite types.
-	***Temporal Trends***: Examining the distribution of meteorite events over time, highlighting periods of increased activity or notable historical occurrences.
-	***Mass and Classification Insights***: Analyzing the relationship between the mass of meteorites and their classifications, potentially revealing patterns related to their origins and the forces that brought them to Earth.

By integrating this rich dataset into our analysis, we're able to not only visualize raw data but also unearth stories about Earth's history and its ongoing interaction with the cosmos.

**Access and Licensing**

The dataset is publicly available under NASA's open data policy, promoting widespread use and dissemination for educational and research purposes. Users can access, download, and employ the data freely, with proper attribution to NASA as the source.
For more detailed information, metadata definitions, and to explore additional resources, please visit the official dataset page: [Meteorite Landings on data.nasa.gov]( https://data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh/about_data).

---
### **Tools**
---

- ***Microsoft Excel*** – Data Cleaning
    - [NASA]( https://data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh/about_data)
- ***Tableau*** – Creating Reports
- ***Microsoft Powerpoint*** – Creating Background Template

---
### **Data Cleaning**
---

In the initial data preparation phase, I performed the following tasks:
1. Data Loading and Inspection.
2. Handling Missing Values,
3. Data Cleaning and Formatting.

---
### **Exploratory Data Analysis**
---

EDA involving exploring the data to answer key questions, such as:
1. **Temporal Analysis**:
  -	How has the frequency of recorded meteorite landings changed over time?
    -	Do certain periods or years show spikes in meteorite discoveries?
    -	Could these trends correlate with historical events, advancements in detection technology, or increased exploration efforts?
  -	Is there a relationship between the year of discovery and the mass of meteorites?
    -	Are larger meteorites more likely to have been found in certain eras?
    - Does the data show that more massive meteorites have been discovered recently due to improved exploration methods?

2. **Geographic Distribution**:
  -	What is the global distribution of meteorite landings?
    -	Which regions have the highest concentration of meteorite finds?
    -	Are there patterns in latitude and longitude indicating meteorites land more frequently in certain areas?
  -	Do meteorite classifications vary by geographic location?
    -	Are specific types of meteorites predominantly found in certain regions?
    -	How does the Earth's magnetic field or atmosphere affect where different meteorites land?

3. **Mass and Classification Insights**:
  -	What is the distribution of meteorite masses?
    -	Is the data skewed toward smaller mass meteorites?
    -	Are there notable outliers with exceptionally large masses?
  -	Is there a correlation between meteorite mass and classification?
    -	Do certain classifications tend to have higher average masses?
    -	Can mass help predict the classification of a meteorite?

4. **Temporal-Spatial Patterns**:
  -	How do meteorite landing locations change over time?
    -	Are there shifts in the geographic distribution of impacts across different decades or centuries?
    -	Do these shifts correlate with human factors like exploration or changes in land use?
  -	Are there clusters of meteorite impacts in specific time frames and locations?
    -	Could these clusters indicate meteor shower events or asteroid fragmentation?

5. **Impact of Discovery Methods**:
  -	Does proximity to populated areas affect the number of meteorite finds?
    -	Are more meteorites found near cities due to higher likelihood of observation?
    -	How does accessibility of terrain influence discovery rates?
  -	How has technology impacted meteorite discoveries over the years?
    -	Is there an increase in finds correlating with advancements in detection equipment?


---
### **Data Analysis**
---

- Created Buckets.
- Creates Measures:
   - ```[]```

---
### **Results**
---


---
### **Recommendations**
---

---
### **Limitations**
---


---
### **References**
---

1. [NASA]( https://data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh/about_data)
