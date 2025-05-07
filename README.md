# Healthcare Appointment No-Show Prediction

## Objective
Predict whether a patient will show up for their medical appointment based on historical data and provide insights to optimize appointment scheduling.

---

## Tools Used
- *Python (Google Colab)* — Data preprocessing, model training using Decision Tree.
- *Scikit-learn, Pandas, Seaborn, Matplotlib* — Data analysis and modeling.
- *Power BI* — Dashboard creation for interactive insights.
- *Pickle* — Model serialization.
- *GitHub* — Project version control and final submission.

---

## Project Files (Deliverables)

| File Name                                             | Description                                             |
|------------------------------------------------------|---------------------------------------------------------|
| Healthcare_Appointment_No_Show_Prediction.ipynb    | Main Colab notebook with code for data cleaning, EDA, modeling. |
| decision_tree_model.pkl                            | Trained Decision Tree model saved using Pickle.         |
| healthcare_no_show_predictions.csv                 | Final dataset with predictions, used in Power BI.       |
| No_Show_Appointment_Insights.pbix                  | Power BI dashboard showing key trends and analysis.     |
| Healthcare_Appointment_No_Show_Optimization_Report.pptx | Optimization suggestions based on insights.         |
| No_Show Appointment_Insights.pdf                   | Final report including Introduction, Abstract, Tools, Steps, and Conclusion. |

---

## Summary of the Approach

1. *Data Cleaning* — Removed irrelevant fields, fixed data types, handled outliers.
2. *Feature Engineering* — Added fields like waiting days and weekday of appointment.
3. *EDA* — Explored factors such as age, SMS reminders, and waiting time.
4. *Modeling* — Trained a Decision Tree classifier for binary prediction (Show/No-Show).
5. *Visualization* — Created Power BI dashboard to show trends and correlations.
6. *Optimization* — Provided actionable recommendations to reduce no-shows.

---

## Optimization Recommendations

- Send SMS reminders more frequently, especially to patients with longer waiting periods.
- Prioritize appointments with short wait times (<3 days) to improve attendance.
- Focus on age groups and weekdays that show high no-show rates.
- Use model predictions to proactively reschedule or confirm risky appointments.

---

## Submission Date: 07 May 2025
