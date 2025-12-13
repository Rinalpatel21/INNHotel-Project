# INN Hotels Project
INN Hotels is a **data analytics and machine learning project** focused on understanding **hotel booking behavior** and predicting **booking cancellations**. Using historical booking data, this project applies **exploratory data analysis (EDA)** and **classification modeling** to identify key factors that influence cancellations and provide actionable recommendations to improve revenue and occupancy rates.

The analysis helps hotel management make **data-driven decisions** related to pricing, booking policies, and customer segmentation.

## Business Problem

Hotel booking cancellations lead to:
- Revenue loss
- Inefficient room utilization
- Operational planning challenges

INN Hotels wants to **predict which bookings are likely to be canceled** so they can take preventive actions such as:
- Overbooking strategies
- Dynamic pricing
- Targeted confirmation policies

This project answers critical questions like:
- What factors drive booking cancellations?
- Can we accurately predict cancellations in advance?
- How can hotels reduce cancellation-related losses?

## Project Goals

1. **Understand booking patterns** through detailed exploratory data analysis  
2. **Identify key drivers of cancellations**  
3. **Build a predictive classification model** to estimate cancellation probability  
4. **Evaluate model performance** using appropriate metrics  
5. **Provide business-focused recommendations** to reduce cancellations and improve revenue

Tools & Skills Used

### Tools & Libraries
- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models & evaluation
- **Jupyter Notebook** – Analysis environment

### Skills Demonstrated
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Supervised Machine Learning (Classification)
- Model Evaluation & Interpretation
- Business Insight Generation
- Data-driven Decision Making

Methodology & Techniques

### 1️⃣ Data Exploration & Cleaning
- Checked missing values and data types
- Analyzed booking lead time, pricing, customer type, and stay duration

### 2️⃣ Exploratory Data Analysis (EDA)
- Compared canceled vs non-canceled bookings
- Visualized relationships between features and cancellations
- Identified trends in booking channels and seasonal demand

### 3️⃣ Feature Engineering
- Encoded categorical variables
- Prepared features for modeling

### 4️⃣ Model Building
- Split data into training and test sets
- Trained classification models (e.g., Logistic Regression, Decision Tree)
- Evaluated performance using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
 
## Key Insights

✔ **Lead Time Matters**  
Bookings made far in advance have a higher likelihood of cancellation.

✔ **Pricing Impact**  
Higher average daily rates are associated with increased cancellation probability.

✔ **Customer Type Influence**  
Transient and online bookings cancel more often than repeat or corporate customers.

✔ **Seasonality Effects**  
Certain months experience higher cancellation rates due to travel patterns.

## Recommendations

📌 **Implement Risk-Based Booking Policies**  
Use the model to flag high-risk bookings and apply stricter cancellation rules.

📌 **Dynamic Pricing Strategy**  
Adjust pricing based on cancellation likelihood and booking lead time.

📌 **Targeted Retention Efforts**  
Send confirmation reminders or incentives to high-risk customers.

📌 **Operational Planning**  
Use predictions to optimize overbooking and room allocation strategies.
