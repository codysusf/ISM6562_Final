<h3>Crash Course: Traffic Crash Analysis Project- README</h3>

<b>Project Overview</b>
This project investigates the environmental, infrastructural, and situational factors that influence traffic crash frequency and severity. Using a cleaned dataset of motor vehicle crash records, the analysis was conducted in Databricks using Spark SQL. The goal is to identify patterns in how weather conditions, road surfaces, traffic control devices, crash types, and vehicle damage levels relate to crash volume and injury outcomes. Visualizations were created to support each analysis and highlight areas of elevated risk. Findings are intended to inform traffic safety strategies and prioritize infrastructure improvements.

<b>Key Research Questions</b>
<li>Do weather or roadway conditions increase crash and fatality rates?
<li>Which crash types are most fatal under specific weather conditions?
<li>Are traffic control devices effective in reducing crash volume?
<li>Is there a relationship between vehicle damage severity and injury count?
<li>Do crashes occur more frequently in specific months, and what are the typical weather conditions?

<b>Summary of Insights</b>
<li><b>Weather & Road Conditions:</b> While clear and dry conditions are associated with the highest volume of crashes, rain on wet roads shows higher fatality risk, indicating increased crash severity.
<li><b>Crash Type & Weather:</b>Crashes involving injuries and tows are most frequent under clear weather, with clear conditions dominating in total fatalities.
<li><b>Traffic Control Devices:</b> Roads with traffic signals and stop signs see the highest crash counts. However, a substantial number of crashes also occur on roads with no traffic control, raising safety concerns.
<li><b>Damage & Injuries:</b> Higher vehicle damage correlates with higher average injuries. Even low-damage crashes can result in significant harm, highlighting the need for attention to minor collisions.
<li><b></b>Monthly Trends:</b> Crash frequency is highest in late summer and early fall (e.g., September, August, July), most often under clear weather. This suggests seasonal traffic volume, rather than weather severity, as a driving factor.

<b>Tools & Technologies</b>
<li>Platform: Databricks
<li>Language: Spark SQL
<li>Data Processing: PySpark DataFrames
<li>Visualizations: Databricks built-in charting features
