# AircraftCrashesPy

**README**

# Project Title: Aircraft Crashes Analysis

![planecrash](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/ca3a6631-852f-49a5-9120-4dd5c8408608)


## Team Members:
- **Kimberly Bonilla** - Flight Personnel
- **Diana Tarasovets** - Cabin Crew
- **Maero Lutta** - Cabin Crew
- **Edgardo Perez Santiago** - First Day Pilot, no training

## Background:
Aviation safety is paramount in the transportation industry, and understanding the historical trends and factors contributing to aviation crashes is essential for improving safety measures. This project delves into aviation crash data dating back to 1908, examining variables such as fatalities, locations, and aircraft operators. By leveraging datasets containing comprehensive crash details and city information, the project aims to uncover patterns and insights that can shed light on the causes and circumstances surrounding aviation accidents over time. Through rigorous analysis of this data, stakeholders in the aviation industry, regulatory bodies, and safety authorities can gain valuable insights to enhance safety protocols, mitigate risks, and prevent future accidents, ultimately contributing to the advancement of aviation safety worldwide.

## Motivation:
Aviation accidents have far-reaching implications, prompting the need for comprehensive analysis to enhance safety protocols and regulations. This project is driven by the imperative to understand the multifaceted factors influencing aviation accidents. By meticulously analyzing crash data spanning over a century, the project seeks to uncover patterns and insights crucial for stakeholders in the aviation industry, regulatory bodies, and safety authorities. Through this analysis, the project aims to provide actionable insights that can inform the development of proactive safety measures, regulatory reforms, and training programs. Ultimately, the project's findings have the potential to contribute significantly to the advancement of aviation safety, reducing the occurrence of accidents and ensuring the well-being of passengers, crew members, and individuals on the ground.

## Questions to answer:
1. What are the aircraft types and operators associated with the highest number of fatalities?
2. When and where did aviation crashes occur, and are there any discernible patterns or trends in terms of time and location?
3. Is there a correlation between the number of passengers on board an aircraft and the fatalities resulting from aviation crashes?

## Tools/Modules Used:
- Python
- Pandas
- Matplotlib
- NumPy
- SciPy

## Datasets Used:
### 1. Airplane Crashes and Fatalities Since 1908:
   - This dataset contains detailed information about aviation crashes, including the date, time, location, operator, aircraft type, number of passengers aboard, fatalities, and a summary of the incident. It spans from 1908 to the present day, providing a comprehensive historical perspective on aviation accidents. The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/cgurkan/airplane-crash-data-since-1908).
   
### 2. World Cities:
   - This dataset provides information about cities worldwide, including their names, geographical coordinates (latitude and longitude), country, population, and administrative details. It serves as a reference for identifying the locations of aviation crashes and analyzing the geographical distribution of incidents. This dataset was obtained from the bootcamp instructor.

Both datasets are stored in the `output_data` directory as flight_data.csv and worldcities.csv and are crucial for conducting the analysis and generating insights into aviation safety and accident patterns.

## Outputs from Exploratory Data Analysis

Crashes vs Year
![1_histogram_Distribution_of_Yrs](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/d52f90f2-e298-4d8d-8528-0e04808a68d5)

Flights vs Year
![2_LineAndFill_FlightsOverTheYrs](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/66488326-9761-4449-b247-85776afedaa7)

Operators vs Year
![3_LineAndFill_OperatorsOverTheYrs](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/fa49750d-e824-4da7-a5f4-bcd38a794feb)

Fatalities vs Year
![4_LineAndFill_FatalitiesOverTheYrs](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/77ba7ca0-11d0-4ff6-8201-a3fb5e15356d)

Distribution of Fatalities
![5_Box_Dist_of_Fatalities_in_AirCrashes](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/ba222604-136b-4f93-92f2-1c34fd669fad)

Survivors vs Year
![6_LineandFill_SurvivorsOvertheYears](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/472e1351-ab65-4cae-90e9-cd659273825d)



## Summary of Analysis:
### 1. Aircraft Types and Operators Associated with the Highest Number of Fatalities:
   - Fatalities in top 20 Aircrafts

![7_hbar_FatalitiesInTop20Aircrafts](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/38ba4bcc-75d0-447a-9c1f-53b11ab395be)
    
   - Fatalities in top 20 Operators

![8_hbar_FatalitiesInTop20Operators](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/742cc245-6552-40cf-969e-9d1b33db81cd)

   - Analysis revealed certain aircraft types and operators consistently associated with the highest number of fatalities. The Douglas DC-3 emerged as the aircraft with the highest fatalities, and Aeroflot, the national airline of Russia, topped the list among operators.



### 2. When and Where Aviation Crashes Occur:
   - Crashes Over the Years

![9_Line_CrashesOvertheYears](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/4159ce14-b141-416c-8bb5-415d143c712b)

   - Fatalities by Month

![10_hbar_Fatalities_by_Month](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/0f6fc14b-79e2-47b9-b3fb-b8d1afa9df6f)


   - Crashes by Decade

![11_bar_Crashes_per_Decade](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/41eaa8b6-e432-4972-8d5e-0585cc5b797e)

   - Geographical Location of Crashes

![crashmap](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/3b3ef49b-65d8-4ddb-9262-6ad461b86379)


   - Top 10 Routes and Fatalities

![13_pie_Top_10_Routes_and_Fatalities](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/71eb1f0b-8c78-4bec-8317-94a7b3d69802)

   - Crashes were more frequent during certain months, with December, September, and August experiencing the highest number of incidents. The United States emerged as the country with the highest number of flight crashes, followed by the Philippines, Colombia, and Russia. Specific routes were associated with a disproportionately high number of fatalities.

### 3. Correlation Between Passenger Numbers and Fatalities:
   - Comparision of Passengers Aboard vs Fatalities

![14_Line_Aboard_vs_Fatalities](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/32ab7c3b-790d-4a0e-9517-fd123ef98187)

   - Relationship between Passenges Aboard & Fatalities

![15_fatalities_vs_aboard_regression](https://github.com/onemanlutta/AircraftCrashesPy/assets/118937365/22762036-d310-4dab-99dc-3e1d3e3dec67)


   - A moderate positive correlation was observed between the number of passengers on board an aircraft and the resulting fatalities from aviation crashes. This underscores the importance of passenger safety measures and emergency response protocols.

## Conclusion:

The analysis of aviation crash data spanning over a century reveals significant insights into the factors influencing fatalities, time, and location of crashes, and the correlation between passenger numbers and fatalities:

1. Aircraft Types and Operators: The Douglas DC-3, Antonov AN-26, and Douglas DC-6B emerged as aircraft types associated with the highest fatalities. Aeroflot, the U.S. Air Force, and major commercial operators like Air France and American Airlines were among the operators with the highest fatalities. Understanding trends associated with these aircraft and operators is vital for implementing targeted safety measures.

2. Time and Location of Crashes: Crashes were more frequent in certain months, particularly December, September, and August, suggesting potential seasonal trends. The 1970s and 1980s saw a higher incidence of accidents, and the United States, Philippines, Colombia, and Russia recorded the highest number of crashes. Specific routes like Tenerife - Las Palmas and Tokyo - Osaka were associated with disproportionately high fatalities, highlighting potential safety concerns.

3. Correlation with Passenger Numbers: A positive correlation was found between the number of passengers on board and fatalities resulting from aviation crashes. An increase in the number of passengers corresponded to a rise in fatalities, indicating the significant role passenger numbers play in accident severity. This underscores the importance of passenger safety measures and emergency protocols to minimize the impact of crashes.

Overall, the analysis provides valuable insights into historical performance, temporal and spatial patterns of crashes, and the relationship between passenger numbers and fatalities. These findings are crucial for informing regulatory reforms, enhancing safety protocols, and mitigating risks to improve aviation safety worldwide. Further exploration and refinement of data and analysis techniques could yield even deeper insights and inform more effective safety strategies in the future.

## Limitations:
- Data Accessibility: Access to comprehensive aviation crash data can be restricted due to confidentiality concerns, national security issues, or proprietary information held by airlines.
- Data Quality: Challenges with data quality, such as missing or inconsistent entries, can affect the accuracy of the analysis.

## Probable Next Steps / Recommendations:
- Data Refinement: Gather more comprehensive and diverse datasets related to aviation incidents, including historical crash data, weather patterns, aircraft performance metrics, pilot records, and air traffic data.
- Feature Engineering: Invest efforts into feature engineering to extract meaningful features from raw data. Explore advanced techniques such as dimensionality reduction, time-series analysis, and anomaly detection to uncover hidden patterns and insights.

*For further details and insights, refer to the detailed analysis in the Jupyter Notebook called project1-FlightFatalitiesPy.ipynb, a ppt with a highlight of this work is also included in output_data called Project1-Group5.pptx.*

--- 

This README provides an overview of the Aircraft Crashes Analysis project, including its background, motivation, questions addressed, tools used, datasets utilized, summary of analysis, limitations, and probable next steps. It serves as a comprehensive guide for understanding the project's objectives, methodologies, findings, and recommendations.# AircraftCrashesPy
