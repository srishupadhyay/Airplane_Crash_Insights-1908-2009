# ✈️ Global Airplane Crashes and Fatalities Insights (1908-2009)

### 1. 📄 **Project Overview**
This project explores major worldwide airplane accidents from 1908 to 2009, aiming to uncover key trends and risk factors that impact aviation safety. With data on crash dates, locations, operators, aircraft types, and fatalities, this analysis identifies patterns in crash frequency, operator performance, high-risk locations, and aircraft models associated with greater fatalities.

By examining these elements, the project provides actionable insights for aviation stakeholders, supporting targeted improvements in safety protocols, operational practices, and maintenance standards. Ultimately, this analysis serves as a data-driven approach to understanding historical aviation safety trends and informing strategies to reduce future accident risks.

---

### 2. ❓ **Core Research Questions**
   - **What are the yearly trends in airplane crashes?**  
   - **Are there any seasonal or monthly patterns in fatalities?**
   - **Which operators have the highest fatality counts, and what insights can be drawn?**
   - **Which locations and urban areas experience the highest ground fatalities?**
   - **What is the distribution of crashes geographically, and are there high-risk regions?**
   - **Which aircraft types are involved in the most fatalities?**
   - **What trends exist in ground fatalities over the years?**


---

### 3. 🗂️ **Data Structure**

<p align="center">
  <a href="https://github.com/srishupadhyay/Airplane_Crash_Insights-1908-2009/tree/79d5aa834b386ec375e8e7007a3d630281011fe3/Dataset">
    Click here to download the dataset in a Microsoft Excel Comma Separated Values File (.csv)
  </a>
</p>


<div align="center">

| **Column**         | **Description**                                      |
|--------------------|------------------------------------------------------|
| **`index`**        | The index of the row                                 |
| **`Date`**         | Date of the incident                                 |
| **`Time`**         | Time of the incident                                 |
| **`Location`**     | Location of the incident                             |
| **`Operator`**     | Operator of the aircraft                             |
| **`Flight #`**     | Flight number of the aircraft                        |
| **`Route`**        | Route taken by the aircraft                          |
| **`Type`**         | Type or model of the aircraft                        |
| **`Registration`** | Registration number of the aircraft                  |
| **`cn/In`**        | Construction or serial number of the aircraft        |
| **`Aboard`**       | Number of people on board the aircraft               |
| **`Fatalities`**   | Number of fatalities in the incident                 |
| **`Ground`**       | Number of people on the ground killed in the incident|
| **`Summary`**      | Summary of the incident                              |

</div>

---

### 4. 📊 **Key Metrics Overview**
   - **Total Crashes Recorded**: 5,199
   - **Total Fatalities**: Approximately 105,000
   - **Average Fatality Count per Crash**: 20.15 deaths
   - **Total Unique Routes**: 3,222

---

### 5. 📋 **Executive Summary**
   This analysis presents a comprehensive look at over 5,000 recorded airplane crashes worldwide, aiming to uncover critical trends and identify high-risk factors. The findings reveal key patterns in crash frequency, operator-related risks, high-risk aircraft types, and geographical hotspots. By addressing questions about yearly trends, operator performance, seasonal impacts, and aircraft-specific risks, the report offers actionable insights for improving aviation safety. The final recommendations focus on targeted operator interventions, enhanced safety protocols for older aircraft models, and seasonal safety campaigns during peak travel times. This project serves as a valuable resource for stakeholders seeking data-driven improvements in aviation safety practices.

---

### 6. 🔍 **Dashboard Analysis & Enhanced Insights**
 <p align="center">
  <a href="https://github.com/srishupadhyay/Airplane_Crash_Insights-1908-2009/blob/65b04982ed79f78db5f540d4a11de49d71536ede/Dasboard-Solution/Airplane%20Crashes%20%26%20Fatalities%20Dashboard.pbix">Click here to download the dashboard Power BI file</a>
</p>

<div align="center">
  <h3>Crash & Fatality Trends</h3>
  <img src="https://github.com/srishupadhyay/Airplane_Crash_Insights-1908-2009/blob/79d5aa834b386ec375e8e7007a3d630281011fe3/Pics/Dashboard%201.png" alt="Crash & Fatality Trends" width="80%">
</div>

<div align="center">
  <h3>Aircraft & Location Analysis</h3>
  <img src="https://github.com/srishupadhyay/Airplane_Crash_Insights-1908-2009/blob/79d5aa834b386ec375e8e7007a3d630281011fe3/Pics/Dashboard%202.png" alt="Aircraft & Location Analysis" width="80%">
</div>

---


**Yearly Crash Trends and Patterns**: The "Crash Incidents by Year" area chart shows a peak of 103 crashes in the year 1972, followed by sustained high numbers until the mid 1990's gradual decline ending at 24 crashes in the year 2009. Here I have used the zoom slider to focus on the peak.

![image](https://github.com/user-attachments/assets/11a01f2b-b53b-4367-8bcb-dfaa6b2f5faa)


**Monthly Fatality Trends**:
- **Highest Fatalities in December**: With 10.3K fatalities and 15.5K people aboard, December shows the highest fatality count compared to the rest. Winter weather conditions, particularly in regions prone to snow, ice, and low visibility, can significantly explain this outcome. December being the global festive season can also explain the high number in loss of lives. Additionally, winter storms and unpredictable weather patterns increase the likelihood of operational delays and mechanical issues, contributing to elevated risk.


- **Lowest Fatalities in June**: The lowest fatalities occur in June, with 7.9K fatalities and 11.6K people aboard. Despite having more people aboard than some other months, fatalities remain low, likely due to favorable summer weather conditions that contribute to safer flight operations. 

<div align="center">
  <img src="https://github.com/user-attachments/assets/cc925c48-5a5b-4868-96a9-bf779d72a171" alt="Image">
</div>


**Fatality Rates by Year**: The highest fatality rate occurred in 1979, with a rate of 0.82 and 89 fatalities among 89 people aboard. This peak suggests a particularly high-risk year, indicating possible gaps in safety protocols at the time.
<div align="center">
  <img src="https://github.com/user-attachments/assets/1060062d-5d4d-4bc7-bbac-36bd2905d7c4" alt="Image">
</div>


**Top Operators by Fatality Count**: 
- Aeroflot: 7,016
- Military operators: 3,717
- Pan American: 1,734
- American Airlines: 1,415
- Air France: 1,302

**Location-Specific Crash Data**:  New York City has an exceptionally high number of 2,750 ground deaths and 163 fatalities. This significant figure highlights the city's status as a high-risk area, likely due to its dense population and the impact of events like the September 11 attacks, which contributed to the overall statistics for ground fatalities.

<div align="center">
    <img src="https://github.com/user-attachments/assets/1f555768-42a8-48ef-808e-bd104f347c00" alt="image">
</div>

  
**Geographic Distribution of Crashes**: The crash locations map displays a global overview of airplane incidents, highlighting areas with a high density of crashes. 
- **Concentration of Crashes**: The map reveals clusters of crash locations primarily in North America, Europe, and parts of Asia, indicating regions with more frequent incidents.
- **High-Density Areas**: Major urban centers and heavily traveled routes show increased crash occurrences.
These insights emphasize the need for targeted safety measures and further investigation into the factors contributing to crash incidents in high-density areas.
<div align="center">
    <img src="https://github.com/user-attachments/assets/a2b21891-f8ce-4149-bb5d-9567e321b644" alt="image">
</div>


**Aircraft Types with Highest Fatalities**: The Douglas DC-3 has the highest fatalities (4.8K), followed by Antonov AN-26 (1.1K) and Douglas DC-6B (1.1K).


**Ground Fatalities by Year**:
- Significant spike in 2001 with 2,891 fatalities due to the September 11 attacks.
- Majority of years show low fatality counts, often below 300.
- Historical trend indicates that ground fatalities were relatively rare prior to 2001.
- Throughout the 20th century, fatalities remained low, with occasional increases but never approaching the 2001 levels.
 <div align="center">
    <img src="https://github.com/user-attachments/assets/568e85dc-dd36-4c75-a9b0-189e764a4479" alt="image">
</div>



---

### 7. ✅ **Enhanced Recommendations**

- Enhance safety protocols by implementing stricter training and guidelines for high-risk operators, particularly Aeroflot and military operators, to help reduce fatalities.
- Launch seasonal safety campaigns, especially in December, to raise awareness about winter-related travel risks and promote safer practices during peak travel times.
- Conduct thorough safety reviews and maintenance checks on older aircraft models, like the Douglas DC-3, which has seen a high number of fatalities.
- Utilize historical data trends to inform policy changes and push for improved regulations in areas that have a higher risk of incidents.
- Enhance emergency preparedness and response strategies for significant events, such as the September 11 attacks, to better equip us to handle future crises.
