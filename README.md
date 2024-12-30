# **Predicting Customer Churn and Satisfaction at Airlines**

## **Project Overview**

The primary goal of this project is to predict customer churn and enhance customer satisfaction within the airline industry. By leveraging data science techniques, we aim to identify at-risk customers, understand the factors influencing customer behavior, and implement targeted strategies to improve loyalty and reduce churn. This will help airlines retain valuable customers, improve their overall service offering, and optimize revenue.

## **Project Objectives**

1. **Churn Prediction**: Develop a predictive model to forecast customer churn based on customer behavior, flight details, and satisfaction ratings.
2. **Customer Satisfaction Analysis**: Analyze key factors that impact customer satisfaction, including service ratings, flight experience, and loyalty status.
3. **Actionable Insights**: Provide actionable recommendations to enhance customer retention and satisfaction based on the predictive model results.
4. **Business Impact**: Help airlines optimize customer retention efforts, improve service offerings, and increase revenue by reducing churn.

## **Data Overview**

The dataset used in this project contains comprehensive customer and flight details, including customer demographics, booking behaviors, flight details, service ratings, and revenue information. The features in the dataset include:

### **Customer Details**
- Customer_ID
- Age, Gender, Location
- Flight details (e.g., Flight ID, Booking Channel, Flight Cancellations)
- Loyalty Tier, Booking Frequency, Miles Accrued

### **Revenue Details**
- Price_of_Ticket
- Revenue_Contribution
- Ancillary_Purchases, Discount_Usage
- Offer type

### **Service Details**
- Ratings for various services (e.g., Inflight Wi-Fi, Seat Comfort, Food and Drink, etc.)
- Complaints Frequency, NPS (Net Promoter Score)
- Delays (Departure and Arrival)
- Recency and AVG_INTERVAL time

## **Methodology**

The project follows these key steps:

1. **Data Cleaning and Preprocessing**: Handling missing values, encoding categorical variables, and normalizing/standardizing numerical features.
2. **Feature Engineering**: Deriving additional features (e.g., frequency of complaints, average interval time) to improve model performance.
3. **Model Development**: Using machine learning algorithms such as Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting to predict customer churn.
4. **Model Evaluation**: Evaluating model performance using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.
5. **Insights Generation**: Analyzing the model's output to generate insights into customer behavior and satisfaction.

## **Tools and Libraries**

The project utilizes the following tools and libraries:

- **Python** for data processing, modeling, and analysis
- **Pandas** and **NumPy** for data manipulation
- **Scikit-learn** for machine learning algorithms and model evaluation
- **Matplotlib** and **Seaborn** for data visualization
- **Jupyter Notebook** for project documentation and execution
