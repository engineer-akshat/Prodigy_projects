# Traffic Accident Data Analysis and Visualization  

This project focuses on analyzing **traffic accident data** to uncover patterns related to **road conditions, weather, and time of day**. The goal is to identify accident hotspots and contributing factors to provide insights that can help improve road safety.

---

## Dataset  
- **Source**: [Kaggle - US Accident EDA](https://www.kaggle.com/code/harshalbhamare/us-accident-eda)  
- **Description**: The dataset contains detailed information about traffic accidents across the United States, including weather conditions, road types, accident severity, and timestamps.  

- **Key Columns**:
  - **Severity**: Indicates the severity of the accident.
  - **Start_Time**: Timestamp of the accident occurrence.  
  - **Weather_Condition**: Weather condition at the time of the accident.  
  - **Road_Condition**: Surface condition of the road.  
  - **Location**: Latitude and longitude of the accident site.  

---

## Project Objectives  
The main goals of the project are:  
1. **Explore and analyze** accident patterns related to road and weather conditions, time of day, and other contributing factors.  
2. **Identify accident hotspots** to highlight areas with high accident occurrences.  
3. **Visualize trends and patterns** using data visualization techniques.  
4. Provide insights into **accident severity** and key factors influencing it.

---

## Tools Used  
- **Python**: Primary language for analysis.  
- **Libraries**:  
  - `pandas` and `numpy` for data manipulation.  
  - `matplotlib` and `seaborn` for visualizations.  
  - `plotly` and `folium` for interactive visualizations and mapping.  
  - `scikit-learn` for feature analysis if needed.

---

## Procedure 

1. **Download the Dataset**:  
   - Visit the Kaggle dataset page from the link provided above and download the dataset.  

2. **Data Preprocessing**:  
   - Load the dataset into a pandas DataFrame.
   - Handle missing or inconsistent values.
   - Convert time columns to appropriate datetime format.
   - Clean weather and road condition data for analysis.

3. **Exploratory Data Analysis (EDA)**:  
   - Analyze accident frequency by **time of day, day of the week, and seasons**.
   - Study the relationship between **weather and road conditions** with accident severity.
   - Group accidents by **location** to identify high-risk areas.

4. **Visualization**:  
   - Create **heatmaps** to highlight accident hotspots.  
   - Plot **bar charts and histograms** for time-based trends.
   - Use **scatter maps** or **choropleth maps** with `folium` or `plotly` to visualize accidents by geographic location.  

---

## Example Insights  
- **Peak Hours**: Identify times when accidents are most frequent (e.g., rush hours).  
- **Weather Patterns**: Examine whether rainy or foggy weather leads to more severe accidents.  
- **Hotspots**: Highlight specific intersections or highways with high accident frequencies.

---

## Conclusion  
This project provides a comprehensive analysis of traffic accidents by studying the influence of environmental and time-based factors. The visualizations and insights can be used to design better traffic management strategies and improve road safety.

---

## Future Improvements  
- Build **predictive models** to forecast accident risks based on weather and time conditions.  
- Create a **real-time dashboard** for monitoring accident patterns.  
- Use **machine learning models** to classify accident severity based on contributing factors.

---

## Author  
- **Akshat Soni**  
