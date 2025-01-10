# Yemeksepeti Order Analysis

##  Motivation
Food ordering platforms like Yemeksepeti play a significant role in modern lifestyles, especially for students managing academic responsibilities. As a student with a busy academic schedule, I observed a pattern of increased food orders during weekends, which seemed to be influenced by the need to relax after a stressful week.

---

##  Dataset Description 
The dataset in this project is derived from two main sources (covering the data from **2024**):

1. **Yemeksepeti Order History:** My personal data from past food orders, including:
   - **Order Date and Time:** The exact time when an order was placed. 
   - **Order Type:** The cuisine type (e.g., pizza, kebab, sushi). 
   - **Day Classification:** Categorization as weekday or weekend. 
   
2. **Academic Calendar:** Personal academic workload data, including:
   - **Class Schedules:** Weekly academic commitments. 
   - **Exam Periods:** Specific dates and times of exams or intensive study periods.

By combining these two data sources, the dataset allows us to analyze the impact of academic workload on food ordering behavior, particularly focusing on weekend order patterns.

---

##   Project Idea 
This project, prepared for the DSA210 (Introduction to Data Science) course, aims to analyze the increase in weekend orders on Yemeksepeti and investigate its connection to academic workload during weekdays. The hypothesis is:

- **Weekend food orders are significantly higher than weekday orders due to reduced academic workload and the need for relaxation.**

The project will provide insights into how external factors influence food ordering behavior.

---

##  Plan 
1. **Data Preparation (Dec 1 - Dec 10):** 
   - Clean and structure the dataset. 
   - Add new features, such as weekday/weekend classification and derived metrics. 

2. **Data Analysis (Dec 11 - Dec 20):** 
   - Perform exploratory data analysis (EDA) to identify trends and patterns.
   - Compare order counts and spending between weekdays and weekends.

3. **Hypothesis Testing (Dec 21 - Dec 31):** 
   - Test if weekend orders are statistically higher than weekday orders.
   - Analyze correlations between academic workload and ordering behavior. 

4. **Visualization (Jan 1 - Jan 8):**
   - Use graphs and charts to illustrate:
     - Order distribution by day.
     - Order trends during exam weeks.
     - Correlation between academic workload and ordering behavior. 

5. **Reporting (Jan 9 - Jan 10):** 
   - Summarize findings and provide actionable insights. 
   - Include visualizations to support conclusions.

---


##  Project Structure
- **`data/`**: Contains the dataset.
  - [orders_cleaned_with_year.csv](data/orders_cleaned_with_year.csv): Cleaned order data with additional features.
- **`scripts/`**: Contains analysis scripts.
  - [dsa210_project.py](scripts/dsa210_project.py): Python script for data analysis.
- **`results/`**: Contains analysis results and visualizations.
  - Order trends and spending pattern graphs.
- **`presentation/`**: Contains the project presentation.
  - [Project Presentation](presentation/yemeksepeti_presentation.pptx): Final project slides.

---

##  Getting Started
1. **Explore the Data:**
   - Check the cleaned dataset in `data/orders_cleaned_with_year.csv`.

2. **Run the Analysis:**
   - Use the script `scripts/dsa210_project.py` to reproduce the analysis.

3. **View the Results:**
   - Review visualizations in `results/` and presentation slides in `presentation/`.

---

##  Future Work
- Include external factors like weather and promotions for deeper insights.
- Utilize predictive modeling for improved understanding of ordering behavior.
- Analyze larger datasets for more generalizable results.

