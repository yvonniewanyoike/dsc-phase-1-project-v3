# Aircraft Risk Analysis Project

## Project Overview
This project identifies the lowest-risk aircraft for the company’s new aviation division by analyzing historical flight safety data.The aviation accident historical data is from the National Transportation Safety Board(NTSB) from 1962 to 2023 and its about civil aviation accidents and selected incidents in the United States and international waters.Through thorough data cleaning, imputation, and risk assessment, I transformed raw accident records into actionable insights to guide strategic purchasing decisions and minimize operational liability.

## Business Problem
Our organization is entering the aviation sector with no prior operational history, creating significant exposure to safety and financial liabilities. Without a data-driven understanding of aircraft reliability, the company risks investing in high-maintenance or accident-prone models. This project identifies aircrafts with the highest safety ratings and lowest historical risk profiles to ensure a secure market entry.

## Objectives
1. To analyze the accidents trends over the years.
2. To identify which aircraft `Make` & `Model` present the highest survival rate
3. To assess whether multi-engine aircraft improve survival chances during emergencies and to determine which engine type offers the highest level of safety.
4. To identify the best-performing aircrafts in adverse weather conditions.
5. To determine the `Hull Loss Ratio` in the case of an incident occurrence.


## Data Understanding
The data used in this project is a csv file named `Aviation_Data`from the National Transportation Safety Board (NTSB) that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

The dataset initially contained 90,348 rows and 31 columns but after thorough data cleaning and feature engineering I eventually worked with 88860 rows and 20 columns.
I worked with the following columns in this analysis:
* Event.Date
* Aircraft.damage
* Aircraft.Category
* Make
* Model
* Amateur.Built
* No.of.Engines
* Engine.Type
* Total.Fatal.Injuries
* Total.Serious.Injuries
* Total.Minor.Injuries
* Total.Uninjured
* Weather.Condition

## Data Analysis
I was able to clean the data set by checking for missing values and duplicate values in the data set. I went a step further to feature engineer more columns in my dataset to help with further analysis and visualized various KPIs in Tableau
https://public.tableau.com/app/profile/yvonnie.wanyoike/vizzes
<img width="1499" height="1199" alt="Aircraft_Risk_Analysis" src="https://github.com/user-attachments/assets/5f65df8f-293e-40cb-9760-388e231e5f29" />


to find the attached visualizations.

## Conclusion
This analysis identifies the safest aircraft for our fleet, providing the Head of Aviation with a low-risk strategy for market entry. The data confirms that aviation safety has improved significantly over the decades due to technological advancements. Specifically, the shift towards multi-engine designs provide a vital safety net during engine failures. Additionally, the high performance and reliability of turbofans and turbojets make them the optimal choice for a safety-first fleet. However, operational safety is heavily dependent on rigorous pre-flight safety checks and the decision-making skills of experienced pilots both of which ensure the safety and success of every flight.

## Recommendations
### Make and Model
I recommend the `Boeing 717-200`, `757-232`, and `777` series, as well as the `Embraer EMB-145LR`, for commercial operations.

For private use, the `Grumman G164B` is well suited for agricultural applications, while the `Consolidated Aeronautics Inc. LAKE LA-4-200` is an amphibious aircraft capable of both land and water operations, making it ideal for ecological surveys and personal transport. The `Piper PA-28` and `PA-18` models are well suited for flight training, and the `Evektor-Aerotechnik AS SPORTSTAR` is suitable for both flight training and touring flights.

For bush flying and wildlife patrol missions, the `Aviat Aircraft Inc. A-1B` is a strong choice. In addition, the `LET BLANIK L-13` is recommended for gliding activities, while the `Robinson Helicopter R22` is an appropriate option in the helicopter category.

### Engine Reliability
I recommend a fleet strategy centered on **multi-engine** aircrafts powered by Turbofan or Turbojet technology. Multi-engine configurations provide critical redundancy, meaning that in the rare event of an engine failure, the aircraft maintains the thrust necessary to land safely. Furthermore, turbine-based engines (turbofans and turbojets) offer significantly higher mechanical reliability compared to older reciprocating engines, leading to the superior survival rates as observed in our data.

### Adverse Weather Resilience
I recommend the `Boeing 737-200` for commercial operations. This model has demonstrated exceptional resilience in adverse weather conditions (IMC) while maintaining a high historical survival rate.

### Hull Loss Ratio
Based on the analysis, I highly recommend the `LET Blanik L-13` and `Boeing 777` due to their elite survival rates and minimal hull loss ratios. For cargo operations, the `McDonnell Douglas DC-10-10` and `MD-11` demonstrate strong safety performance with low attrition rates. Additionally, the `Boeing 757` is an ideal candidate for fleet modernization, as it offers superior safety metrics compared to the `727-200` models it was designed to replace.



