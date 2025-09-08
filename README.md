🏥 Healthcare Appointment No-Show Prediction
--------------------------------------------
📌 Project Overview

Missed medical appointments (no-shows) create challenges for healthcare providers, wasting resources and reducing access for other patients.
This project predicts the likelihood of patient no-shows using machine learning and provides insights for scheduling optimization.

🚀 Deliverables
-----------------

Prediction Model → Decision Tree classifier (tree_model.pkl, predictions.csv)

Power BI Dashboard → Visual insights (Elevate_Project.pbix)

Report → 2-page summary (NoShow_Project_Report.pdf)

🔧 Tools & Technologies
-------------------------

Python: Pandas, Scikit-learn, Matplotlib, Seaborn, Joblib

Power BI: KPIs, visualizations, dashboards

Google Colab / Jupyter: Data cleaning, EDA, model training

📊 Steps Performed
-------------------

Data Cleaning → Removed invalid ages, standardized columns, parsed dates

Feature Engineering → Waiting days, age bands, weekdays, SMS reminders

EDA → Identified trends (SMS effectiveness, weekday patterns, age group risks)

Modeling → Trained Decision Tree, evaluated with accuracy, precision, recall, confusion matrix

Dashboarding → Power BI for interactive insights (KPIs, confusion matrix, risk distribution)

Recommendations → Reduce waiting time, extra reminders for high-risk patients, apply selective overbooking

📈 Insights
-----------------

SMS reminders reduce no-show rates significantly

Longer waiting times → higher no-show probability

Younger patients tend to miss appointments more than older patients

Mondays and Fridays often have higher no-shows

✅ Recommendations
-------------------

Send extra reminders (SMS/calls) to high-risk patients

Reduce waiting time between scheduling and appointment

Consider smart overbooking in high no-show slots

Spread out high-risk patients across time slots


✨ This project demonstrates how predictive analytics + BI dashboards can improve healthcare scheduling efficiency.
